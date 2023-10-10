<template>
  <div class="flex items-center flex-col gap-4 photo-slide">
    <img
      :src="image"
      alt="instrutor photo"
      class="border-solid border-4 border-primary-color rounded-sm"
    />
    <p class="text-base text-gray-300">{{ name }}</p>
    <p class="text-xs text-gray-300">{{ description }}</p>
  </div>
</template>

<script>
export default {
  name: 'InstructorImageProps',
  props: ['image', 'name', 'description']
}
</script>

<style scoped>
.photo-slide {
  width: 48%;
}
.photo-img {
  width: 630px;
}

@media (max-width: 677px) {
  .photo-slide {
    width: 100%;
  }
}
</style>
