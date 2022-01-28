<template>
  <div>
      <intro d-text="Our Blog" />
      <blog />
      <blog-2 />
  </div>
</template>

<script>
import Blog from '~/components/blog.vue'
import Blog2 from '~/components/blog2.vue'
import intro from '~/components/intro.vue'
export default {
  components: { intro, Blog, Blog2 },

}
</script>

<style>

</style>