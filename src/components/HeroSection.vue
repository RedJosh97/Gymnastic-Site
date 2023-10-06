<template>
  <div class="relative -z-50 -mt-12 object-cover">
    <img src="/public/image/Rectangle 4.png" alt="background-image" />
  </div>
  <div class="px-20 pb-16 absolute top-0 left-0 right-0">
    <div class="max-w-xl">
      <p
        id="design-style"
        class="text-white font-sans max-w-md text-5xl font-extrabold mt-36 leading-snug"
      >
        <span id="design-style" class="text-5xl font-extrabold">unleash</span> your Inner Athlete
      </p>
      <p class="text-white mt-9 mb-9 text-md font-medium">
        Get ready to sweat it out and achieve your fitness goals with our high-energy fitness
        classes! Our classes are designed to cater to all fitness levels and provide a fun and
        motivating environment to help you reach your peak performance.
      </p>
      <button class="px-12 py-3 text-white bg-primary-color text-md">Start for free</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroSection'
}
</script>

<style>
span {
  font-family: 'Orbitron';
  color: transparent;
  -webkit-text-stroke-width: 1px;
  -webkit-text-stroke-color: var(--primary-color);
}

#design-style {
  font-family: 'Orbitron';
}
</style>
