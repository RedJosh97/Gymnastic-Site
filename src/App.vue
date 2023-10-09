<template>
  <div class="app">
    <NavBarSection />
    <HeroSection />
    <!-- <ImageProduct /> -->
    <FitStyle />
    <ClassTimeline />
    <InstructorSlide />
    <DownloadPlatform />
    <QuestionSection />
    <TestimonialSlide />
    <FooterSection />
  </div>
</template>

<script>
import NavBarSection from './components/NavBarSection.vue'
import HeroSection from './components/HeroSection.vue'
// import ImageProduct from './components/ImageProduct.vue'
import FitStyle from './components/FitStyle.vue'
import ClassTimeline from './components/ClassTimeline.vue'
import InstructorSlide from './components/InstructorSlide.vue'
import DownloadPlatform from './components/DownloadPlatform.vue'
import QuestionSection from './components/QuestionSection.vue'
import TestimonialSlide from './components/TestimonialSlide.vue'
import FooterSection from './components/FooterSection.vue'

export default {
  name: 'app',
  components: {
    NavBarSection,
    HeroSection,
    // ImageProduct,
    FitStyle,
    ClassTimeline,
    InstructorSlide,
    DownloadPlatform,
    TestimonialSlide,
    FooterSection,
    QuestionSection
  }
}
</script>

<style>
.app {
  margin: auto;
  max-width: 1440px;
}
</style>
