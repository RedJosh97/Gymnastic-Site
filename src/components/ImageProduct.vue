<template>
  <div class="bg-gray-950 relative px-20">
    <div class="blur-md -mt-4 absolute top-0 left-0 right-0 h-12 w-full bg-gray-950"></div>
    <div class="pt-28">
      <HeadingProps title="Find what moves you" />
    </div>
    <div class="wrapper flex gap-10 mt-16">
      <div class="flex gap-7 flex-col">
        <div class="image-blur">
          <img src="/public/image/image 9.png" />
        </div>
        <div class="flex gap-8">
          <p class="text-2xl text-gray-400 font-bold">GYM</p>
          <p class="text-xs text-gray-400 font-bold leading-5">
            Expect a heart-pumping workout that will leave you feeling energized and accomplished.
            Our supportive community of like-minded individuals.
          </p>
        </div>
      </div>
      <div class="group-wrapper">
        <div class="card-container">
          <div class="image-blur">
            <img src="/public/image/image 10.png" class="card-wrapper-img" />
          </div>
        </div>
        <p class="content">Zumba</p>
      </div>
      <div class="group-wrapper">
        <div class="card-container">
          <div class="image-blur">
            <img src="/public/image/image 11.png" class="card-wrapper-img" />
          </div>
        </div>
        <p class="content">Yoga</p>
      </div>
      <div class="group-wrapper">
        <div class="card-container">
          <div class="image-blur">
            <img src="/public/image/image 12.png" class="card-wrapper-img" />
          </div>
        </div>
        <p class="content">Martial Arts</p>
      </div>
    </div>
  </div>
</template>

<script>
import HeadingProps from './HeadingProps.vue'
export default {
  name: 'ImageProduct',
  components: {
    HeadingProps
  }
}
</script>

<style scoped>
.card-container {
  min-width: 180px;
  padding: 15px;
  position: relative;
}
.card-wrapper-img {
  border-radius: 40px 0px 0 0;
  object-fit: cover;
  display: block;
  height: 360px;
  position: relative;
}

.image-blur {
  position: relative;
}

.image-blur::after {
  content: '';
  width: 100%;
  height: 100%;
  background: linear-gradient(to top, rgba(0, 0, 0, 0.9), transparent);
  top: 0;
  left: 0;
  right: 0;
  position: absolute;
}
.content {
  text-align: center;
  color: rgb(169, 169, 169);
  font-size: 18px;
  margin-top: -58px;
  font-weight: 900;
  z-index: 20;
  position: absolute;
  bottom: 55px;
  right: 0;
  left: 0;
}

.group-wrapper {
  position: relative;
}
</style>
