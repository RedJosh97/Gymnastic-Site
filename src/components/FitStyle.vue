<template>
  <div class="pt-14 -z-50 -mt-3 bg-gray-950 h-full relative pb-20">
    <HeadingProps title="Fit for your style" />
    <div class="flex justify-center flex-col items-center">
      <p class="fit-style text-gray-400 pt-8 max-w-2xl text-center text-base leading-5">
        Wake up with a sunrise meditation, sweat it out with lunchtime HIIT, or unwind with an
        evening flow. You’ll find movement for every mood with classes sorted by time, style, and
        skill level.
      </p>
      <div class="clipper absolute bottom-48 right-0 w-1/5 h-10">.</div>
      <div class="clipper absolute bottom-12 right-0 w-3/5 h-10">.</div>
      <div class="relative">
        <img class="fit-img max-w-2xl pt-8" src="/public/image/Rectangle 10.png" />
        <img
          class="fit-img max-w-2xl absolute -bottom-2 -left-2.5 -z-30"
          src="/public/image/Rectangle 11.png"
        />
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

@media (max-width: 800px) {
  .fit-style {
    max-width: 70%;
    font-size: calc(3px + 2vw);
  }

  .fit-img {
    width: 450px;
  }
}

@media (max-width: 552px) {
  .fit-img {
    width: 350px;
  }
}
@media (max-width: 500px) {
  .fit-img {
    width: 280px;
  }
}
</style>
