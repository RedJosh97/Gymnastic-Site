<template>
  <div class="-mt-2 relative">
    <div>
      <img src="/public/image/Rectangle 12.png" />
    </div>
    <div class="px-20 absolute top-0 bottom-0 z-10 w-full">
      <HeadingProps title="Classes" />
      <div class="flex gap-12 justify-between items-center">
        <ClassImageProps />
      </div>
      <button class="max-md:px-2 px-12 py-3 text-white bg-primary-color text-md">See all</button>
    </div>
  </div>
</template>

<script>
import ClassImageProps from './ClassImageProps.vue'
import HeadingProps from './HeadingProps.vue'

export default {
  name: 'ClassTimeline',
  components: { HeadingProps, ClassImageProps }
}
</script>

<style scoped>
.class-style {
  background: green;
  height: 410px;
}
</style>
