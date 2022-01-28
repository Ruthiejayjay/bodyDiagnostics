<template>
  <div>
    <b-header />
    <teams />
    <cta />
    <testimonial />
    <faq />
    
    <!-- <blog /> -->
  </div>
</template>

<script>
import bHeader from '~/components/bHeader.vue'
import Cta from '~/components/cta.vue'
// import Blog from '~/components/blog.vue'
import Faq from '~/components/faq.vue'
import Teams from '~/components/teams.vue'
import Testimonial from '~/components/testimonial.vue'
export default {
  components: { bHeader, Teams, Testimonial, Faq, Cta},
  name: 'IndexPage'
}
</script>
