<template>
  <div id="gallery" class="bg-gray-900 px-20 flex-wrap py-12">
    <HeadingProps title="Instructors" />
    <div class="flex max-lg:flex-wrap pt-10 justify-between items-center gap-5">
      <InstructorImageProps
        :image="'/public/image/Rectangle 17.png'"
        name="Jacob Jones"
        description="Gym trainer"
      />
      <InstructorImageProps
        :image="'/public/image/Rectangle 18.png'"
        name="Lesley Alexander"
        description="Gym trainer"
      />
      <InstructorImageProps
        :image="'/public/image/Rectangle 19.png'"
        name="Cameroon Williamson"
        description="Gym trainer"
      />
      <InstructorImageProps
        :image="'/public/image/Rectangle 20.png'"
        name="Jane Cooper"
        description="Gym trainer"
      />
    </div>
  </div>
</template>

<script>
import HeadingProps from './HeadingProps.vue'
import InstructorImageProps from './InstructorImageProps.vue'

export default {
  name: 'InstructorSlide',
  components: {
    HeadingProps,
    InstructorImageProps
  }
}
</script>

<style scoped></style>
