<template>
  <div class="bg-black bg-opacity-40 p-8">
    <p class="text-gray-400 text-medium">{{ content }}</p>
    <div class="flex gap-2">
      <i class="lar la-star text-primary-color font-bold"></i>
      <i class="lar la-star text-primary-color font-bold"></i>
      <i class="lar la-star text-primary-color font-bold"></i>
      <i class="lar la-star text-primary-color font-bold"></i>
      <i class="lar la-star text-primary-color font-bold"></i>
    </div>
    <div class="flex justify-between gap-4 items-center pt-5">
      <img :src="profileImage" class="w-12" />
      <p class="text-gray-400 text-sm">{{ name }}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TestimonialContentProps',
  props: ['name', 'profileImage', 'content']
}
</script>

<style scoped></style>
