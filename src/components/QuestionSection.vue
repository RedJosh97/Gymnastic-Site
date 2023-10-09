<template>
  <div class="px-20 py-10 bg-gray-950 h-screen w-full">
    <HeadingProps title="Frequently ask question" />
    <div>
      <p class="text-white">What are your focus areas as a UI/UX agency?</p>
      <button class="text-white font-semibold">+</button>
    </div>
    <div class="p-8 bg-orange-900">
      <p class="change-font">
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
        been the industry's standard dummy text ever since the 1500s, when an unknown printer took a
        galley of type and scrambled it to make a type specimen book. It has survived not only five
        centuries, but also the leap into electronic typesetting, remaining essentially unchanged.It
        was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum
        passages, and more recently with desktop
      </p>
    </div>
  </div>
</template>

<script>
import HeadingProps from './HeadingProps.vue'

export default {
  name: 'QuestionSection',
  components: { HeadingProps }
}
</script>

<style></style>
