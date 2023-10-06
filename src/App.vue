<template>
  <div class="app">
    <NavBarSection />
    <HeroSection />
    <LifeStyle />
  </div>
</template>

<script>
import NavBarSection from './components/NavBarSection.vue'
import HeroSection from './components/HeroSection.vue'
import LifeStyle from './components/LifeStyle.vue'

export default {
  name: 'app',
  components: {
    NavBarSection,
    HeroSection,
    LifeStyle
  }
}
</script>

<style>
.app {
  margin: auto;
  max-width: 1440px;
}
</style>
