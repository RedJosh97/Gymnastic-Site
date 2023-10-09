<template>
  <div class="relative -z-50 -mt-12">
    <img
      class="w-screen object-top object-cover"
      src="/public/image/Rectangle 4.png"
      alt="background-image"
    />
  </div>
  <div id="hero-content" class="max-md:px-6 px-20 pt-14 absolute top-0 left-0 right-0">
    <button @click="openMenu" class="hamburger pointer md:hidden rounded-md bg-white">
      <i class="las la-bars text-2xl p-1 text-primary-color font-extrabold"></i>
    </button>
    <div class="max-w-xl">
      <p
        id="design-style"
        class="max-md:text-4xl text-white font-sans max-w-md text-5xl font-extrabold mt-36 leading-snug"
      >
        <span id="design-style" class="max-md:text-4xl text-5xl font-extrabold">unleash</span> your
        Inner Athlete
      </p>
      <p
        class="max-md:text-xs max-md:leading-6 max-md:mt-4 text-white mt-12 mb-10 text-md font-medium"
      >
        Get ready to sweat it out and achieve your fitness goals with our high-energy fitness
        classes! Our classes are designed to cater to all fitness levels and provide a fun and
        motivating environment to help you reach your peak performance.
      </p>
      <button class="max-md:px-2 max-md:rounded-md px-12 py-3 text-white bg-primary-color text-md">
        Start for free
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroSection',
  data() {
    closeDiag: false
  },
  methods: {
    openMenu() {
      this.$emit('closeDiag')
      console.log('open menu')
    }
  }
}
</script>

<style>
span {
  font-family: 'Orbitron';
  color: transparent;
  -webkit-text-stroke-width: 1px;
  -webkit-text-stroke-color: var(--primary-color);
}

#design-style {
  font-family: 'Orbitron';
}

@media (max-width: 1024px) {
  #hero-content {
    margin-top: -4rem;
  }
}
@media (max-width: 760px) {
  #hero-content {
    margin-top: -8rem;
  }
}

@media only screen and (max-width: 767px) {
  .hamburger {
    display: block;
    position: absolute;
    top: 12px;
    z-index: 1000;
    right: 20px;
  }
}
</style>
