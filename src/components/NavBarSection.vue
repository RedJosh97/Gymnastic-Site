<template>
  <div class="flex justify-between w-full items-center px-20 z-20 max-md:px-6">
    <p class="text-primary-color font-extrabold text-2xl">SPYRO</p>
    <ul class="flex gap-6 text-white text-md max-md:hidden">
      <NavigatorList />
    </ul>
    <div class="flex items-center gap-4">
      <button class="max-md:px-2 px-12 py-3 text-white bg-primary-color text-md">Contact Us</button>
      <button @click="openMenu = !openMenu" class="md:hidden pointer rounded-md bg-white">
        <i class="las la-bars text-xl p-1 text-primary-color font-extrabold"></i>
      </button>
    </div>
    <div
      v-if="openMenu"
      class="navi w-2/6 h-3/5 bg-primary-color rounded-tl-3xl justify-around flex items-center absolute md:hidden z-10 top-14 opacity-90 right-0"
    >
      <NavigatorList />
    </div>
  </div>
</template>

<script>
import NavigatorList from './NavigatorList.vue'
export default {
  name: 'NavBarSection.vue',
  components: {
    NavigatorList
  },
  data() {
    return {
      openMenu: true,
      list: []
    }
  }
}
</script>
