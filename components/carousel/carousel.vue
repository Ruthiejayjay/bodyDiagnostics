<template>
  <div bg-white font-sans leading-normal tracking-normal>
    <div class="carousel relative shadow-2xl bg-white">
      <div class="carousel-inner relative overflow-hidden w-full">
        <!--Slide 1-->
        <input
          class="carousel-open"
          type="radio"
          id="carousel-1"
          name="carousel"
          aria-hidden="true"
          hidden=""
          checked="checked"
        />
        <div class="carousel-item absolute opacity-0" style="height: 50vh">
          <div
            class="
              block
              h-full
              w-full
              bg-indigo-500
              text-white text-5xl text-center
            "
          >
            Slide 1
          </div>
        </div>
       
        <!--Slide 2-->
        <input
          class="carousel-open"
          type="radio"
          id="carousel-2"
          name="carousel"
          aria-hidden="true"
          hidden=""
        />
        <div class="carousel-item absolute opacity-0" style="height: 50vh">
          <div
            class="
              block
              h-full
              w-full
              bg-orange-500
              text-white text-5xl text-center
            "
          >
            Slide 2
          </div>
        </div>
        <!--Slide 3-->
        <input
          class="carousel-open"
          type="radio"
          id="carousel-3"
          name="carousel"
          aria-hidden="true"
          hidden=""
        />
        <div class="carousel-item absolute opacity-0 h-90">
          <div
            class="
              block
              h-full
              w-full
              bg-green-500
              text-white text-5xl text-center
            "
          >
            <img src="~/assets/bd3.jpg">
            <h2 class="text-white">Our Hospital</h2>
          </div>
        </div>
       
        <!-- Add additional indicators for each slide-->
        <ol class="carousel-indicators">
          <li class="inline-block mr-3">
            <label
              for="carousel-1"
              class="
                carousel-bullet
                cursor-pointer
                block
                text-4xl text-white
                hover:text-blue-700
              "
              >•</label
            >
          </li>
          <li class="inline-block mr-3">
            <label
              for="carousel-2"
              class="
                carousel-bullet
                cursor-pointer
                block
                text-4xl text-white
                hover:text-blue-700
              "
              >•</label
            >
          </li>
          <li class="inline-block mr-3">
            <label
              for="carousel-3"
              class="
                carousel-bullet
                cursor-pointer
                block
                text-4xl text-white
                hover:text-blue-700
              "
              >•</label
            >
          </li>
        </ol>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.carousel-open:checked + .carousel-item {
  position: static;
  opacity: 100;
}
.carousel-item {
  -webkit-transition: opacity 0.6s ease-out;
  transition: opacity 0.6s ease-out;
}
#carousel-1:checked ~ .control-1,
#carousel-2:checked ~ .control-2,
#carousel-3:checked ~ .control-3 {
  display: block;
}
.carousel-indicators {
  list-style: none;
  margin: 0;
  padding: 0;
  position: absolute;
  bottom: 2%;
  left: 0;
  right: 0;
  text-align: center;
  z-index: 10;
}
#carousel-1:checked
  ~ .control-1
  ~ .carousel-indicators
  li:nth-child(1)
  .carousel-bullet,
#carousel-2:checked
  ~ .control-2
  ~ .carousel-indicators
  li:nth-child(2)
  .carousel-bullet,
#carousel-3:checked
  ~ .control-3
  ~ .carousel-indicators
  li:nth-child(3)
  .carousel-bullet {
  color: #2b6cb0; /*Set to match the Tailwind colour you want the active one to be */
}
</style>