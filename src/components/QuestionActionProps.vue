<template>
  <div>
    <div class="flex justify-between py-4 items-center border-b-4 solid gap-7 border-gray-400">
      <p class="text-white">{{ title }}</p>
      <button
        v-if="(changeToggle = !changeToggle)"
        @click="toggleBtn = !toggleBtn"
        class="text-white text-3xl font-semibold"
      >
        +
      </button>
      <button v-else @click="toggleBtn = !toggleBtn" class="text-white text-xl font-semibold">
        <i class="las la-angle-down"></i>
      </button>
    </div>
    <div v-if="toggleBtn" class="p-8 bg-orange-900 transform -skew-x-12 max-md:skew-x-0">
      <p class="change-font">
        {{ content }}
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'QuestionActionProps.vue',
  data() {
    return {
      toggleBtn: false,
      changeToggle: true,
      emit: ['close']
    }
  },

  //   methods: {
  //     dialog() {

  //     },
  // close() {
  //   document.addEventListener('keydown', (e) => {
  //     if (e.key === 'Escape') {
  //       this.$emit('close')
  //       // Or any other way you want to close your modal
  //     }
  //   })
  // }
  //   },
  props: ['title', 'content']
}
</script>

<style scoped>
.change-font {
  font-size: calc(9.5px + 0.4vw);
  color: white;
}
</style>
