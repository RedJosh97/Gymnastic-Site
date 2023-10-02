<template>
  <div class="flex justify-between w-full items-center">
    <p class="text-primary-color font-extrabold text-4xl">SPYRO</p>
    <ul class="flex gap-6 text-white text-lg">
      <li>Classes</li>
      <li>About Us</li>
      <li>Team</li>
      <li>Gallery</li>
    </ul>
    <div>
      <button class="btn">Contact Us</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavBarSection.vue'
}
</script>

<style>
.btn {
  @apply px-12 py-3 text-white bg-primary-color text-lg;
}
</style>
