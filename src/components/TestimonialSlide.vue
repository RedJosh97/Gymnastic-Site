<template>
  <div class="relative">
    <img src="/public/image/Rectangle 12.png" />
    <div class="absolute top-0 left-0 right-0 px-20 pt-10">
      <HeadingProps title="Client Feeback" />
      <div class="pt-10">
        <TestimonialContentProps
          content="Al-Balad is essentially Jeddah old town. It was once surrounded by a wall, but now only the gates rendering"
          :profileImage="'/public/image/Ellipse 5.png'"
          name="Courtney Henry"
        />
      </div>
    </div>
  </div>
</template>

<script>
import HeadingProps from './HeadingProps.vue'
import TestimonialContentProps from './TestimonialContentProps.vue'

export default {
  name: 'TestimonialSlide',
  components: { TestimonialContentProps, HeadingProps }
}
</script>

<style scoped></style>
