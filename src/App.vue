<template>
  <div class="app">
    <NavBarSection />
    <HeroSection />
    <ImageProduct />
    <FitStyle />
  </div>
</template>

<script>
import NavBarSection from './components/NavBarSection.vue'
import HeroSection from './components/HeroSection.vue'
import ImageProduct from './components/ImageProduct.vue'
import FitStyle from './components/FitStyle.vue'

export default {
  name: 'app',
  components: {
    NavBarSection,
    HeroSection,
    ImageProduct,
    FitStyle
  }
}
</script>

<style>
.app {
  margin: auto;
  max-width: 1440px;
}
</style>
