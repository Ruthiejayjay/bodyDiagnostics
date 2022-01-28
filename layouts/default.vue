<template>
  <div v-if="alphineready">
      <navigation />
      <nuxt />
      <b-footer />
  </div>
</template>

<script>
import BFooter from '~/components/bFooter.vue'
import navigation from '~/components/navigation.vue'
export default {
  components: { navigation, BFooter },

 data() {
    return {
      alphineready: false,
    };
  },

  head() {
    return {
      title: "Body Diagnostics", // Other meta information
      script: [
        {
          hid: "alphine",
          src: "https://cdnjs.cloudflare.com/ajax/libs/alpinejs/2.8.0/alpine.js",
          // Changed after script load
          callback: () => {
            this.alphineready = true;
          },
        },
      ],
    };
  },
}
</script>

<style>

</style>