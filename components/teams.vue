<template>
  <!-- Section 1 -->
  <section class="bg-white">
    <div
      class="
        pt-16
        pb-16
        pl-4
        pr-4
        mx-auto
        ml-auto
        mr-auto
        bg-top bg-cover
        max-w-7xl
        md:px-24
        lg:px-12 lg:py-20
      "
    >
      <div
        class="
          mb-10
          ml-auto
          mr-auto
          bg-top bg-cover
          max-w-7xl
          md:mx-auto
          sm:text-center
          lg:max-w-2xl
          md:mb-16
        "
      >
        <p
          class="
            inline-block
            px-3
            py-px
            mb-3
            text-sm
            font-semibold
            tracking-wider
            text-white
            uppercase
            bg-yellow-600
            rounded-full
          "
        >
          Our Staff
        </p>
        <div
          class="
            mb-6
            ml-auto
            mr-auto
            font-sans
            tracking-tight
            text-gray-900
            bg-top bg-cover
            max-w-7xl
            md:mx-auto
          "
        >
          <p
            class="
              inline
              max-w-lg
              text-3xl
              font-bold
              leading-none
              tracking-tight
              text-gray-900
              sm:text-5xl
              md:mx-auto
            "
          >
            Meet The Team
          </p>
        </div>
        <p class="text-base text-gray-700 md:text-lg">
          We love the work we do and we love the amazing people we work with.
          Check out our awesome team of individuals below.
        </p>
      </div>
      <div class="grid gap-10 sm:grid-cols-2 lg:grid-cols-4">
        <!-- Team Member 1 -->
        <div>
          <div class="relative overflow-hidden rounded-md shadow-lg group">
            <img
              class="object-cover w-full h-72 xl:h-80"
              src="~/assets/nurse.png"
              alt="Team Member Name"
            />
            <div
              class="
                absolute
                inset-0
                px-6
                py-4
                text-center
                duration-300
                opacity-0
                group-hover:opacity-100
              "
            >
              <div
                class="
                  absolute
                  inset-0
                  w-full
                  h-full
                  bg-gradient-to-br
                  from-yellow-500
                  opacity-60
                  to-pink-600
                "
              ></div>
              <div
                class="
                  relative
                  flex flex-col
                  items-center
                  justify-center
                  w-full
                  h-full
                "
              >
                <p class="mb-1 text-lg font-bold text-white">John Smith</p>
                <p class="mb-4 text-xs text-blue-50">Founder &amp; CEO</p>
                <p class="mb-4 text-xs tracking-wide text-blue-50">
                  John has a family of three and enjoys hiking.
                </p>
              </div>
            </div>
          </div>
        </div>

        <!-- Team Member 2 -->
        <div>
          <div class="relative overflow-hidden rounded-md shadow-lg group">
            <img
              class="object-cover w-full h-72 xl:h-80"
              src="~/assets/nurse (1).jpg"
              alt="Team Member Name"
            />
            <div
              class="
                absolute
                inset-0
                px-6
                py-4
                text-center
                duration-300
                opacity-0
                group-hover:opacity-100
              "
            >
              <div
                class="
                  absolute
                  inset-0
                  w-full
                  h-full
                  bg-gradient-to-br
                  from-yellow-500
                  opacity-60
                  to-pink-600
                "
              ></div>
              <div
                class="
                  relative
                  flex flex-col
                  items-center
                  justify-center
                  w-full
                  h-full
                "
              >
                <p class="mb-1 text-lg font-bold text-white">Sean Jackson</p>
                <p class="mb-4 text-xs text-blue-50">Co-Founder</p>
                <p class="mb-4 text-xs tracking-wide text-blue-50">
                  Sean's passionate about drawing, art, and photography.
                </p>
              </div>
            </div>
          </div>
        </div>

        <!-- Team Member 3 -->
        <div>
          <div class="relative overflow-hidden rounded-md shadow-lg group">
            <img
              class="object-cover w-full h-72 xl:h-80"
              src="~/assets/nurse (2).jpg"
              alt="Team Member Name"
            />
            <div
              class="
                absolute
                inset-0
                px-6
                py-4
                text-center
                duration-300
                opacity-0
                group-hover:opacity-100
              "
            >
              <div
                class="
                  absolute
                  inset-0
                  w-full
                  h-full
                  bg-gradient-to-br
                  from-yellow-500
                  opacity-60
                  to-pink-600
                "
              ></div>
              <div
                class="
                  relative
                  flex flex-col
                  items-center
                  justify-center
                  w-full
                  h-full
                "
              >
                <p class="mb-1 text-lg font-bold text-white">Fred Jenson</p>
                <p class="mb-4 text-xs text-blue-50">Product Lead</p>
                <p class="mb-4 text-xs tracking-wide text-blue-50">
                  Fred is a Coffee Connoisseur who also loves to ski.
                </p>
              </div>
            </div>
          </div>
        </div>

        <!-- Team Member 4 -->
        <div>
          <div class="relative overflow-hidden rounded-md shadow-lg group">
            <img
              class="object-cover w-full h-72 xl:h-80"
              src="~/assets/nurse (3).jpg"
              alt="Team Member Name"
            />
            <div
              class="
                absolute
                inset-0
                px-6
                py-4
                text-center
                duration-300
                opacity-0
                group-hover:opacity-100
              "
            >
              <div
                class="
                  absolute
                  inset-0
                  w-full
                  h-full
                  bg-gradient-to-br
                  from-yellow-500
                  opacity-60
                  to-pink-600
                "
              ></div>
              <div
                class="
                  relative
                  flex flex-col
                  items-center
                  justify-center
                  w-full
                  h-full
                "
              >
                <p class="mb-1 text-lg font-bold text-white">Jeremy Lee</p>
                <p class="mb-4 text-xs text-blue-50">Lead Engineer</p>
                <p class="mb-4 text-xs tracking-wide text-blue-50">
                  Jeremy loves to spend time with his family and go to the gym.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
</style>