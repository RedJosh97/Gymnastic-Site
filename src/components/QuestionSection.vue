<template>
  <div class="px-20 py-10 bg-gray-950 h-full w-full">
    <HeadingProps title="Frequently ask question" />

    <div>
      <QuestionActionProps
        content="Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
        been the industry's standard dummy text ever since the 1500s, when an unknown printer took a
        galley of type and scrambled it to make a type specimen book. It has survived not only five
        centuries, but also the leap into electronic typesetting, remaining essentially unchanged.It
        was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum
        passages, and more recently with desktop"
        title="What are your focus areas as a UI/UX agency?"
      />
      <QuestionActionProps
        content="Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
        been the industry's standard dummy text ever since the 1500s, when an unknown printer took a
        galley of type and scrambled it to make a type specimen book. It has survived not only five
        centuries, but also the leap into electronic typesetting, remaining essentially unchanged.It
        was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum
        passages, and more recently with desktop"
        title="Why is UI/UX design important for your business growth?"
      />
      <QuestionActionProps
        content="Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
        been the industry's standard dummy text ever since the 1500s, when an unknown printer took a
        galley of type and scrambled it to make a type specimen book. It has survived not only five
        centuries, but also the leap into electronic typesetting, remaining essentially unchanged.It
        was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum
        passages, and more recently with desktop"
        title="Can your UX design agency help us with web design?"
      />
      <QuestionActionProps
        content="Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
        been the industry's standard dummy text ever since the 1500s, when an unknown printer took a
        galley of type and scrambled it to make a type specimen book. It has survived not only five
        centuries, but also the leap into electronic typesetting, remaining essentially unchanged.It
        was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum
        passages, and more recently with desktop"
        title="How much does a UI/UX design project cost?"
      />
    </div>

    <div
      class="max-md:skew-x-0 max-md:flex-col p-14 transform -skew-x-12 gap-6 bg-primary-color items-center flex justify-between mt-20 w-full h-full"
    >
      <div class="flex flex-col gap-5 max-w-md min-w-min">
        <p class="text-white font-bold text-2xl">Are you ready to Change?</p>
        <p class="text-white text-xs leading-5">
          Challenge your strength. Stretch your body. Breathe easy. Our team of world-class
          instructors will empower
        </p>
      </div>
      <div>
        <button
          class="max-md:skew-x-0 w-56 transform py-2 px-9 text-white -skew-x-12 border-2 solid border-white"
        >
          Start your free trial
        </button>
      </div>
    </div>
  </div>
</template>

<script>
import HeadingProps from './HeadingProps.vue'
import QuestionActionProps from './QuestionActionProps.vue'

export default {
  name: 'QuestionSection',
  data() {
    return {
      toggleBtn: false
    }
  },
  components: {
    HeadingProps,
    QuestionActionProps
  }
}
</script>

<style></style>
