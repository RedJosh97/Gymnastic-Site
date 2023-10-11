<template>
  <div id="team" class="overflow relative">
    <img src="/public/image/Rectangle 12.png" class="h-screen w-screen" />
    <div class="testimonial-display absolute top-0 left-0 right-0 px-20 pt-14">
      <HeadingProps title="Client Feeback" />
      <div class="testimonial-float pt-16 flex gap-7 justify-between items-center">
        <TestimonialContentProps
          content="Al-Balad is essentially Jeddah old town. It was once surrounded by a wall, but now only the gates rendering"
          :profileImage="'/public/image/Ellipse 5.png'"
          name="Courtney Henry"
        />
        <TestimonialContentProps
          content="I had been to Al Balad several times. It is one of my favorite places in Jeddah. It is historic, ful"
          :profileImage="'/public/image/Ellipse 5-2.png'"
          name="Jane Cooper"
        />
        <TestimonialContentProps
          content="Al-Balad is essentially Jeddah old town. It was once surrounded by a wall, but now only the gates rendering"
          :profileImage="'/public/image/Ellipse 5.png'"
          name="Courtney Henry"
        />
        <TestimonialContentProps
          content="This a great historic site to visit. I rented a little cart and the driver was a really good friendly"
          :profileImage="'/public/image/Ellipse 5-1.png'"
          name="Brooklyn Simmon"
        />
      </div>
    </div>
  </div>
</template>

<script>
import HeadingProps from './HeadingProps.vue'
import TestimonialContentProps from './TestimonialContentProps.vue'

export default {
  name: 'TestimonialSlide',
  components: {
    TestimonialContentProps,
    HeadingProps
  }
}
</script>

<style scoped>
@media (max-width: 1024px) {
  .overflow {
    overflow: hidden;
  }

  .testimonial-float {
    overflow-x: scroll;
  }

  .testimonial-display {
    padding: 0 3rem;
  }
}
</style>
