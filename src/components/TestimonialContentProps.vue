<template>
  <div
    class="testimonial border-b-8 border-primary-color bg-black bg-opacity-40 p-8 flex gap-5 flex-col"
  >
    <p class="font-change text-gray-400 h-20">{{ content }}</p>
    <div class="flex gap-2">
      <i class="lar la-star text-primary-color font-bold"></i>
      <i class="lar la-star text-primary-color font-bold"></i>
      <i class="lar la-star text-primary-color font-bold"></i>
      <i class="lar la-star text-primary-color font-bold"></i>
      <i class="lar la-star text-primary-color font-bold"></i>
    </div>
    <div class="pt-7 flex gap-6 items-center">
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

<style>
.testimonial {
  max-width: 530px;
  min-width: 240px;
}

.font-change {
  font-size: calc(4px + 1vw);
}
</style>
