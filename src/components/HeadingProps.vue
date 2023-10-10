<template>
  <div class="flex justify-center text-center">
    <h3 class="font-style text-gray-400 font-bold text-4xl">{{ title }}</h3>
  </div>
</template>

<script>
export default {
  name: 'HeadingProps',
  props: ['title']
}
</script>

<style scoped>
@media (max-width: 500px) {
  .font-style {
    font-size: calc(14px + 4vw);
  }
}
</style>
