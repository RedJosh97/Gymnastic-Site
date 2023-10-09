<template>
  <div class="flex justify-between w-full items-center px-20 max-md:px-6">
    <p class="text-primary-color font-extrabold text-2xl">SPYRO</p>
    <ul class="flex gap-6 text-white text-md max-md:hidden">
      <li>Classes</li>
      <li>About Us</li>
      <li>Team</li>
      <li>Gallery</li>
    </ul>
    <div>
      <button class="max-md:px-2 px-12 py-3 text-white bg-primary-color text-md">Contact Us</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavBarSection.vue',
  emits: ['closeDiag']
}
</script>

<style></style>
