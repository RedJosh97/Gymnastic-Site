<template>
  <div class="pt-14 bg-gray-950 h-screen relative">
    <HeadingProps title="Fit for your style" />
    <div class="flex justify-around flex-col items-center">
      <p class="text-white pt-8 max-w-xl text-center">
        Wake up with a sunrise meditation, sweat it out with lunchtime HIIT, or unwind with an
        evening flow. You’ll find movement for every mood with classes sorted by time, style, and
        skill level.
      </p>
      <div class="clipper absolute bottom-20 right-0 w-1/5 h-10">hellow</div>
      <div class="clipper absolute bottom-2 right-0 bg-green-300 w-3/5 h-10">hellow</div>
      <div>
        <div class="design">
          <div>
            <img class="max-w-md pt-8" src="/public/image/Rectangle 10.png" />
          </div>
        </div>
        <div class="design-out">
          <img class="" src="/public/image/Rectangle 11.png" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import HeadingProps from './HeadingProps.vue'

export default {
  name: 'FitStyle',
  components: { HeadingProps }
}
</script>

<style scoped>
.clipper {
  opacity: 0.1;
  background: var(--Linear, linear-gradient(90deg, #ff4300 -6.33%, #ff6400));
}

.design {
  border: 1px solid red;
  position: relative;
  z-index: 1;
}
</style>
