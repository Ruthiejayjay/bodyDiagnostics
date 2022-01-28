<template>
  <div>
    <!-- Section 1 -->
    <section
      class="relative w-full h-auto bg-no-repeat bg-cover bgImg"
      x-data="{ showMenu: false }"
    >
      <div
        class="
          absolute
          inset-0
          z-0
          h-full
          bg-gradient-to-br
          from-pink-400
          opacity-60
          to-yellow-500
        "
      ></div>

      <!-- Desktop menu -->
      <div class="flex items-center w-full h-20"></div>

      <!-- Mobile Menu -->
      <div
        x-show.transition="showMenu"
        class="
          absolute
          top-0
          z-20
          flex flex-col
          items-center
          justify-center
          w-full
          h-full
          space-y-5
          text-lg
          origin-center
          bg-pink-500
        "
        x-cloak=""
      >
        <a href="#_" class="block text-pink-200 hover:text-white">First Link</a>
        <a href="#_" class="block text-pink-200 hover:text-white"
          >Second Link</a
        >
        <a href="#_" class="block text-pink-200 hover:text-white">Third Link</a>
      </div>
      <!-- End Mobile Menu -->

      <div
        class="container flex items-center justify-center h-auto py-32 mx-auto"
      >
        <div class="z-10 flex flex-col items-center px-8 xl:px-0">
          <h1
            class="
              mx-6
              mt-1
              text-lg text-2xl
              font-black
              text-center text-white
              lg:text-4xl
              sm:text-center sm:mx-0
            "
          >
            Your Life, Our Passion <br class="block lg:hidden" />Discover Body
            Disgnostics!
          </h1>
          <!-- <p class="w-2/3 my-6 text-xl font-normal text-center text-gray-200">
            The ultimate toolset to help you expand your creative portfolio,
            craft your skills, and build the next million dollar applicaiton.
          </p> -->
          <div class="flex justify-center md:mt-10">
            <a
              href="#"
              class="
                px-8
                py-2
                m-2
                text-center text-white
                bg-yellow-500
                border-2 border-yellow-500
                rounded-full
                hover:bg-transparent
              "
              >Online Booking</a
            >
            <a
              href="#"
              class="
                px-8
                py-2
                m-2
                text-center text-white
                border-2 border-yellow-500
                rounded-full
                hover:bg-yellow-500
              "
              >Contact Us</a
            >
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style>
.bgImg {
  background-image: url("~assets/bd3.jpg");
  height: 100vh;
}
</style>