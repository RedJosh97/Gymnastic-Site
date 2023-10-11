<template>
  <!-- class="-mt-2 relative h-full down" -->
  <div id="classes" class="relative h-full down">
    <div>
      <img src="/public/image/Rectangle 12.png" class="background-class-image w-full" />
    </div>
    <!-- absolute top-0 bottom-0 z-10 down -->
    <div class="cont-display px-20 pt-5 absolute top-0 bottom-0 z-10 down">
      <HeadingProps title="Classes" />
      <div>
        <div class="class-image-access flex gap-16 justify-between mt-5 items-center">
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
        <div class="btn-class flex justify-center items-center absolute bottom-3 left-0 right-0">
          <button class="px-12 py-3 text-white bg-primary-color text-md">See all</button>
        </div>
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

<style scoped>
@media (max-width: 939px) {
  .class-image-access {
    display: flex;
    margin: 0 auto;
    flex-direction: column;
    width: 50%;
    gap: 12px;
    margin-top: 18px;
  }

  .cont-display {
    padding-top: 34px;
    position: inherit;
    background: rgba(1, 3, 23, 0.9);
  }

  .btn-class {
    position: static;
  }

  .background-class-image {
    display: none;
  }
}

/* @media (max-width: 660px) {
  .class-image-access {
    display: flex;
    margin: 0 auto;
    flex-direction: column;
    width: 50%;
    gap: 12px;
    margin-top: 18px;
  }
} */
@media (max-width: 660px) {
  .class-image-access {
    width: 50%;
    gap: 30px;
  }

  .btn-class {
    margin-top: 30px;
  }
}
</style>
