<template>
  <div class="app">
    <NavBarSection />
    <HeroSection />
    <ImageProduct />
    <FitStyle />
    <ClassTimeline />
    <InstructorSlide />
    <DownloadPlatform />
    <TestimonialSlide />
  </div>
</template>

<script>
import NavBarSection from './components/NavBarSection.vue'
import HeroSection from './components/HeroSection.vue'
import ImageProduct from './components/ImageProduct.vue'
import FitStyle from './components/FitStyle.vue'
import ClassTimeline from './components/ClassTimeline.vue'
import InstructorSlide from './components/InstructorSlide.vue'
import DownloadPlatform from './components/DownloadPlatform.vue'
import TestimonialSlide from './components/TestimonialSlide.vue'

export default {
  name: 'app',
  components: {
    NavBarSection,
    HeroSection,
    ImageProduct,
    FitStyle,
    ClassTimeline,
    InstructorSlide,
    DownloadPlatform,
    TestimonialSlide
  }
}
</script>

<style>
.app {
  margin: auto;
  max-width: 1440px;
}
</style>
