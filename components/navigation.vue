<template>
  <div class="bg-gradient-to-br from-yellow-700 to-yellow-400">
    <nav
      x-data="{ mobile: false }"
      class="
        relative
        z-40
        py-10
        pt-6
        mx-auto
        md:pb-6
        max-w-7xl
        md:flex md:justify-between md:items-center
        w-full
      "
    >
      <div class="relative z-20 flex items-center justify-between">
        <div>
          <a href="/" class="md:text-xl">
            <img src="~/assets/golden4.png" />
          </a>
        </div>

        <!-- Mobile menu button -->
        <div x-on:click="mobile = !mobile" class="flex md:hidden">
          <button
            type="button"
            class="
              text-gray-200
              hover:text-gray-100
              focus:outline-none focus:text-gray-100
            "
            aria-label="toggle menu"
          >
            <svg viewBox="0 0 24 24" class="w-6 h-6 fill-current">
              <path
                fill-rule="evenodd"
                d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"
              ></path>
            </svg>
          </button>
        </div>
      </div>

      <!-- Mobile Menu open: "block", Menu closed: "hidden" -->
      <div
        x-bind:class="{ hidden: !mobile, flex: mobile }"
        class="
          left-0
          z-10
          items-center
          justify-center
          w-full
          font-semibold
          select-none
          md:flex
          lg:absolute
        "
      >
        <div
          class="
            flex flex-col
            justify-center
            w-full
            mt-4
            space-y-2
            md:mt-0 md:flex-row md:space-x-6
            lg:space-x-10
            xl:space-x-16
            md:space-y-0
          "
        >
          <div
            x-data="{ isOpen: false }"
            x-on:mouseenter="isOpen = true"
            x-on:mouseleave="isOpen = false"
            class="relative py-3"
          >
            <div
              class="
                relative
                z-10
                flex
                items-center
                space-x-1
                text-gray-300
                cursor-pointer
                lg:space-x-3
                hover:text-gray-200
                focus:outline-none
              "
            >
              <span>About Us</span>
              <svg
                class="w-5 h-5"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </div>

            <div
              x-show="isOpen"
              x-transition:enter="transition ease-out duration-200"
              x-transition:enter-start="opacity-0 translate-y-1"
              x-transition:enter-end="opacity-100 translate-y-0"
              x-transition:leave="transition ease-in duration-150"
              x-transition:leave-start="opacity-100 translate-y-0"
              x-transition:leave-end="opacity-0 translate-y-1"
              class="
                absolute
                left-0
                z-20 z-30
                w-full
                p-3
                mt-3
                -ml-0
                space-y-2
                overflow-hidden
                transform
                shadow-lg
                bg-gradient-to-br
                from-yellow-800
                to-yellow-900
                lg:left-1/2 lg:-ml-24
                md:w-48
                rounded-xl
                ring-1 ring-black ring-opacity-5
              "
              x-cloak=""
            >
              <Nuxt-link
              to="info1"
                class="
                  block
                  px-4
                  py-3
                  text-sm text-gray-200
                  capitalize
                  cursor-pointer
                  hover:bg-yellow-900
                  rounded-xl
                  hover:text-gray-200
                "
              >
                Who We Are
              </Nuxt-link>
              <a
                href="info2"
                class="
                  block
                  px-4
                  py-3
                  text-sm text-gray-200
                  capitalize
                  hover:bg-yellow-900
                  rounded-xl
                  hover:text-gray-200
                "
              >
                Quality Statement
              </a>
              <a
                href="info3"
                class="
                  block
                  px-4
                  py-3
                  text-sm text-gray-200
                  capitalize
                  hover:bg-yellow-900
                  rounded-xl
                  hover:text-gray-200
                "
              >
                Our Core Values
              </a>
            </div>
          </div>
          <NuxtLink
            to="/contact"
            class="py-3 text-gray-300 hover:text-gray-100 hover:underline"
            >Contact Us</NuxtLink
          >
          <NuxtLink
            to="blog"
            class="py-3 text-gray-300 hover:text-gray-100 hover:underline"
            >Our Blog</NuxtLink
          >
          <div
            x-data="{ isOpen: false }"
            x-on:mouseenter="isOpen = true"
            x-on:mouseleave="isOpen = false"
            class="relative py-3"
          >
            <div
              class="
                relative
                z-10
                flex
                items-center
                space-x-1
                text-gray-300
                cursor-pointer
                lg:space-x-3
                hover:text-gray-200
                focus:outline-none
              "
            >
              <span>Services</span>
              <svg
                class="w-5 h-5"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </div>

            <div
              x-show="isOpen"
              x-transition:enter="transition ease-out duration-200"
              x-transition:enter-start="opacity-0 translate-y-1"
              x-transition:enter-end="opacity-100 translate-y-0"
              x-transition:leave="transition ease-in duration-150"
              x-transition:leave-start="opacity-100 translate-y-0"
              x-transition:leave-end="opacity-0 translate-y-1"
              class="
                absolute
                left-0
                z-20 z-30
                w-full
                p-3
                mt-3
                -ml-0
                space-y-2
                overflow-hidden
                transform
                shadow-lg
                bg-gradient-to-br
                from-yellow-800
                to-yellow-900
                lg:left-1/2 lg:-ml-24
                md:w-48
                rounded-xl
                ring-1 ring-black ring-opacity-5
              "
              x-cloak=""
            >
              <a
                href="imaging"
                class="
                  block
                  px-4
                  py-3
                  text-sm text-gray-200
                  capitalize
                  cursor-pointer
                  hover:bg-yellow-900
                  rounded-xl
                  hover:text-gray-200
                "
              >
                Medical Imaging
              </a>
              <a
                href="physiotherapy"
                class="
                  block
                  px-4
                  py-3
                  text-sm text-gray-200
                  capitalize
                  hover:bg-yellow-900
                  rounded-xl
                  hover:text-gray-200
                "
              >
                Physiotherapy
              </a>
              <a
                href="diagnostics"
                class="
                  block
                  px-4
                  py-3
                  text-sm text-gray-200
                  capitalize
                  hover:bg-yellow-900
                  rounded-xl
                  hover:text-gray-200
                "
              >
                DNA and Molecuar Diagnostics
              </a>
              <a
                href="laboratory"
                class="
                  block
                  px-4
                  py-3
                  text-sm text-gray-200
                  capitalize
                  hover:bg-yellow-900
                  rounded-xl
                  hover:text-gray-200
                "
              >
                Laboratory
              </a>
            </div>
          </div>
        </div>
      </div>

      <div
        x-bind:class="{ flex: mobile, 'hidden md:flex': !mobile }"
        class="
          relative
          z-20
          flex-col
          justify-center
          pr-5
          mt-4
          space-y-8
          md:pr-3
          lg:pr-0
          md:flex-row md:space-y-0 md:items-center md:space-x-6 md:mt-0
        "
      ></div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>