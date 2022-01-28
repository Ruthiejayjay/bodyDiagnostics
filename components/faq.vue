<template>
  <!-- Section 1 -->
  <section class="py-24 bg-yellow-900">
    <div class="max-w-3xl px-8 mx-auto lg:px-16">
      <h2 class="mb-2 text-xl font-bold text-white md:text-3xl">
        Frequently Asked Questions
      </h2>

      <div class="relative mt-2 mt-8">
        <!-- Question 1 -->
        <div
          x-data="{ show: false }"
          class="relative overflow-hidden text-white select-none"
        >
          <h4
            x-on:click="show = !show"
            class="
              flex
              items-center
              justify-between
              py-5
              text-lg
              font-medium
              text-gray-100
              cursor-pointer
              sm:text-xl
              hover:text-white
            "
          >
            <span>How to book for an appointment</span>
            <svg
              class="
                w-6
                h-6
                text-yellow-400
                transition-all
                duration-200
                ease-out
                transform
                rotate-0
                fill-current
              "
              :class="{ '-rotate-45': show }"
              stroke="currentColor"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M12 6v6m0 0v6m0-6h6m-6 0H6"
              ></path>
            </svg>
          </h4>
          <p
            class="px-1 pt-0 mt-1 text-yellow-300 sm:text-lg py-7"
            x-transition:enter="transition-all ease-out duration-300"
            x-transition:enter-start="opacity-0 transform -translate-y-4"
            x-transition:enter-end="opacity-100 transform -translate-y-0"
            x-transition:leave="transition-all ease-out hidden duration-200"
            x-transition:leave-start="opacity-100 transform -translate-y-0"
            x-transition:leave-end="opacity-0 transform -translate-y-4"
            x-show="show"
            x-cloak=""
          >
            Call our call centre number or book online by using the form above
          </p>
        </div>

        <!-- Question 2 -->
        <div
          x-data="{ show: false }"
          class="relative overflow-hidden text-white select-none"
        >
          <h4
            x-on:click="show = !show"
            class="
              flex
              items-center
              justify-between
              py-5
              text-lg
              font-medium
              text-gray-100
              cursor-pointer
              sm:text-xl
              hover:text-white
            "
          >
            <span>Do I need to prepare for my Procedure?</span>
            <svg
              class="
                w-6
                h-6
                text-yellow-400
                transition-all
                duration-200
                ease-out
                transform
                rotate-0
                fill-current
              "
              :class="{ '-rotate-45': show }"
              stroke="currentColor"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M12 6v6m0 0v6m0-6h6m-6 0H6"
              ></path>
            </svg>
          </h4>
          <p
            class="px-1 pt-0 mt-1 text-yellow-300 sm:text-lg py-7"
            x-transition:enter="transition-all ease-out duration-300"
            x-transition:enter-start="opacity-0 transform -translate-y-4"
            x-transition:enter-end="opacity-100 transform -translate-y-0"
            x-transition:leave="transition-all ease-out hidden duration-200"
            x-transition:leave-start="opacity-100 transform -translate-y-0"
            x-transition:leave-end="opacity-0 transform -translate-y-4"
            x-show="show"
            x-cloak=""
          >
            Some procedures may require special booking arrangements and
            preparations before arrival. These include • Hysterosalpingogram
            (HSG). • Barium meal/Enema • Endoscopy • Paediatric MRI • Paediatric
            EEG • Digital mammogram • Pap smear • DNA for paternity testing •
            Biopsies • Interventional procedures • Procedures requiring local or
            general anaesthesia Kindly contact our service Centre…
          </p>
        </div>

        <!-- Question 3 -->
        <div
          x-data="{ show: false }"
          class="relative overflow-hidden text-white select-none"
        >
          <h4
            x-on:click="show = !show"
            class="
              flex
              items-center
              justify-between
              py-5
              text-lg
              font-medium
              text-gray-100
              cursor-pointer
              sm:text-xl
              hover:text-white
            "
          >
            <span>How do I make Payments?</span>
            <svg
              class="
                w-6
                h-6
                text-yellow-400
                transition-all
                duration-200
                ease-out
                transform
                rotate-0
                fill-current
              "
              :class="{ '-rotate-45': show }"
              stroke="currentColor"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M12 6v6m0 0v6m0-6h6m-6 0H6"
              ></path>
            </svg>
          </h4>
          <p
            class="px-1 pt-0 mt-1 text-yellow-300 sm:text-lg py-7"
            x-transition:enter="transition-all ease-out duration-300"
            x-transition:enter-start="opacity-0 transform -translate-y-4"
            x-transition:enter-end="opacity-100 transform -translate-y-0"
            x-transition:leave="transition-all ease-out hidden duration-200"
            x-transition:leave-start="opacity-100 transform -translate-y-0"
            x-transition:leave-end="opacity-0 transform -translate-y-4"
            x-show="show"
            x-cloak=""
          >
            Image Diagnostics accepts various payment modes such as • Cash •
            Bank Transfer • POS • Valid bank cheques
          </p>
        </div>

        <!-- Question 4 -->
        <div
          x-data="{ show: false }"
          class="relative overflow-hidden text-white select-none"
        >
          <h4
            x-on:click="show = !show"
            class="
              flex
              items-center
              justify-between
              py-5
              text-lg
              font-medium
              text-gray-100
              cursor-pointer
              sm:text-xl
              hover:text-white
            "
          >
            <span>Any Advantage for on-line booking</span>
            <svg
              class="
                w-6
                h-6
                text-yellow-400
                transition-all
                duration-200
                ease-out
                transform
                rotate-0
                fill-current
              "
              :class="{ '-rotate-45': show }"
              stroke="currentColor"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M12 6v6m0 0v6m0-6h6m-6 0H6"
              ></path>
            </svg>
          </h4>
          <p
            class="px-1 pt-0 mt-1 text-yellow-300 sm:text-lg py-7"
            x-transition:enter="transition-all ease-out duration-300"
            x-transition:enter-start="opacity-0 transform -translate-y-4"
            x-transition:enter-end="opacity-100 transform -translate-y-0"
            x-transition:leave="transition-all ease-out hidden duration-200"
            x-transition:leave-start="opacity-100 transform -translate-y-0"
            x-transition:leave-end="opacity-0 transform -translate-y-4"
            x-show="show"
            x-cloak=""
          >
            We encourage pre-booking arrangements to save time and guarantee timely service. Terms and conditions apply.
          </p>
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