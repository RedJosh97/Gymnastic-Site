<template>
  <div class="mt-56 blur-md bg-gray-950 h-10 z-10"></div>
  <div class="bg-gray-900 -mt-5 px-20 pt-14">
    <HeadingProps title="Find what moves you" />
    <!-- <div class="gb-yellow-400 h-screen">
      <div></div>
      <div class="relative w-52 bg-gray-500">
        <img class="card min-h-4 h-80 absolute" src="/public/image/image 10.png" />
        <p class="text-green-300 absolute bottom-2 right-0">Zumba</p>
      </div>
      <div>1</div>
    </div> -->
    <!-- flex gap-10 items-center mt-10 -->
    <div class="card-wrapper mb">
      <div class="card-container special flex flex-col">
        <img class="special-img" src="/public/image/image 9.png" />
        <div class="flex gap-12">
          <p class="font-bold text-gray-500 text-2xl">GYM</p>
          <p class="font-bold text-gray-500 text-sm">
            Expect a heart-pumping workout that will leave you feeling energized and accomplished.
            Our supportive community of like-minded individuals.
          </p>
        </div>
      </div>
      <div class="card-container">
        <img class="card-container-img" src="/public/image/image 10.png" />
        <div class="card-content">
          <p>Zumba</p>
        </div>
      </div>
      <div class="card-container">
        <img class="card-container-img" src="/public/image/image 11.png" />
        <div class="card-content">
          <p>Yoga</p>
        </div>
      </div>
      <div class="card-container">
        <img class="card-container-img" src="/public/image/image 12.png" />
        <div class="card-content">
          <p>Martial Art</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import HeadingProps from './HeadingProps.vue'

export default {
  naem: 'LifeStyle',
  components: {
    HeadingProps
  }
}
</script>

<style scoped>
.card-container {
  margin: 0 auto;
  /* min-width: 180px;
  width: 100%; */
  padding: 5px;
  position: relative;
  border: 1px solid red;
}

.image-background {
  z-index: -1000;
  position: relative;
}
.card-container-img {
  object-fit: cover;
  height: 330px;
  /* min-width: 120px; */
  border-radius: 40px 0 0 0;
}
.card-container::after {
  content: '';
  position: absolute;
  width: 100%;
  height: 100%;
  outline: none;
  border: none;
  background: linear-gradient(60deg, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0));
  border-radius: 40px 0 0 0;
  right: 0;
  bottom: 0;
}

.card-content {
  width: 100%;
  position: absolute;
  bottom: 18px;
  left: 0;
  z-index: 1000;
}

.card-content p {
  text-align: center;
  color: rgb(200, 193, 193);
  font-weight: 600;
  font-size: 1.5rem;
}

.special {
  /* width: 520px; */
}
.card-wrapper {
  display: grid;
  grid-template-columns: 450px 1fr 1fr 1fr;
  grid-template-rows: 330px;
  gap: 34px;
  /* flex-wrap: wrap; */
}
</style>
