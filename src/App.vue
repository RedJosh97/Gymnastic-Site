<template>
  <div class="app">
    <NavBarSection />
    <HeroSection />
  </div>
</template>

<script>
import NavBarSection from './components/NavBarSection.vue'
import HeroSection from './components/HeroSection.vue'

export default {
  name: 'app',
  components: {
    NavBarSection,
    HeroSection
  }
}
</script>

<style>
.app {
  margin: auto;
  max-width: 1440px;
}
</style>
