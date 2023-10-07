<template>
  <div class="-mt-2 relative">
    <div>
      <img src="/public/image/Rectangle 12.png" />
    </div>
    <div class="px-20 absolute top-0 bottom-0 z-10 w-full">
      <HeadingProps title="Classes" />
      <div class="flex gap-16 justify-between mt-5 items-center">
        <ClassImageProps
          sport="Yoga"
          :classImage="'/public/image/Rectangle 13.png'"
          student="22"
          time="3H"
          instructor="Esther Howard"
          title="Strenght & Sweat"
          classes="30"
          difficulty="Beginner"
        />
        <ClassImageProps
          sport="Fitness"
          :classImage="'/public/image/Rectangle 13-1.png'"
          student="34"
          time="4H"
          instructor="Wade Warren"
          title="Total Body Burnout"
          classes="45"
          difficulty="Medium"
        />
        <ClassImageProps
          sport="Yoga"
          :classImage="'/public/image/Rectangle 13-2.png'"
          student="62"
          time="3H"
          instructor="Robert Fox"
          title="BootCamp Challenge"
          classes="52"
          difficulty="Hard"
        />
      </div>
      <div class="mt-7 flex justify-center">
        <button class="max-md:px-2 px-12 py-3 text-white bg-primary-color text-md">See all</button>
      </div>
    </div>
  </div>
</template>

<script>
import ClassImageProps from './ClassImageProps.vue'
import HeadingProps from './HeadingProps.vue'

export default {
  name: 'ClassTimeline',
  components: {
    HeadingProps,
    ClassImageProps
  }
}
</script>

<style scoped></style>
