<template>
  <div class="w-auto text-6xl text-left p-20 bg-yellow-700 opacity-80 text-white intro">
      {{ dText }}
    </div>
</template>

<script>
export default {
props: ['dText'] 
}
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Squada+One&display=swap");

.intro {
  font-family: "Squada One", cursive;
}
</style>