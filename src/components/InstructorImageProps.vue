<template>
  <div class="flex items-center flex-col gap-1">
    <img
      :src="image"
      alt="instrutor photo"
      class="w-4/5 border solid border-primary-color rounded-sm"
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

<style scoped></style>
