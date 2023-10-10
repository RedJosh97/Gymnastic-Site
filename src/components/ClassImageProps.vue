<template>
  <div class="class-style">
    <div class="relative flex justify-center">
      <img :src="classImage" class="class-image" />
      <img
        src="/public/image/Rectangle 11.png"
        class="class-image-clipper absolute bottom-3 left-0 right-0 -z-10"
      />
    </div>
    <div class="flex justify-between -mt-3">
      <p class="text-gray-200 text-xs">
        <i class="las la-check-circle text-[#ff6400]"></i> {{ sport }}
      </p>
      <p class="text-gray-200 text-xs">
        <i class="las la-user-plus text-[#ff6400]"></i> {{ student }} Student
      </p>
    </div>
    <div class="flex justify-between items-center">
      <p class="text-gray-300 text-base font-bold">{{ title }}</p>
      <p class="text-gray-300 text-xs font-medium"><i class="las la-history"></i> {{ time }}</p>
    </div>
    <p class="text-gray-300 text-xs">Instructor: {{ instructor }}</p>
    <p class="text-gray-300 text-xs">
      <i class="text-primary-color las la-dot-circle"></i> Number of classes: {{ classes }}
    </p>
    <p class="text-gray-300 text-xs">
      <i class="text-primary-color las la-dot-circle"></i> Difficulty: {{ difficulty }}
    </p>

    <div class="flex justify-between">
      <button class="py-2 px-2 text-xs transform -skew-x-12 bg-primary-color text-white">
        Learn more
      </button>
      <button
        class="py-2 px-4 text-xs transform -skew-x-12 bg-transparent text-gray-200 border-solid border-2"
      >
        Start a free trial
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ClassImageProps',
  props: ['student', 'sport', 'classImage', 'time', 'instructor', 'difficulty', 'classes', 'title']
}
</script>

<style scoped>
.class-image {
  width: 97%;
  height: 89%;
  object-fit: cover;
}
.class-style {
  display: flex;
  flex-direction: column;
  padding: 7px 0;
  /* min-width: 200px; */
  gap: 12px;
  height: 410px;

  .class-image:hover {
    border: 1.8px solid var(--primary-color);
  }
}

@media (max-width: 939px) {
  .class-style {
    min-width: 530px;
    height: 580px;
  }

  .class-image-clipper {
    max-width: 530px;
  }
}
@media (max-width: 660px) {
  .class-style {
    width: 300px;
    /* display: none; */
    /* height: 580px; */
  }

  .class-image {
    width: 100%;
  }
  .class-image-clipper {
    width: 100%;
  }

  .class-style {
    height: auto;
    min-width: auto;
  }
}
</style>
