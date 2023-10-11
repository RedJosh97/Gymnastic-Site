<template>
  <div id="aboutus" class="relative">
    <img src="/public/image/Rectangle 49.png" />
    <div
      class="absolute max-2xl:bg-gray-950 top-0 left-0 px-20 py-12 right-0 flex gap-9 flex-col justify-center items-center"
    >
      <h3 class="text-3xl font-bold text-primary-color">SPYRO</h3>
      <p class="font-change text-center text-gray-400 max-w-3xl">
        Join us today and experience the transformative power of our fitness classes. Don't wait to
        start your fitness journey. Take the first step towards a healthier, stronger you. Let's
        sweat, have fun, and make fitness a way of life together!
      </p>
      <div class="flex justify-center gap-5 items-center">
        <i class="social lab la-facebook-f"></i>
        <i class="social lab la-twitter"></i>
        <i class="social lab la-instagram"></i>
        <i class="social lab la-linkedin-in"></i>
        <i class="social lab la-whatsapp"></i>
      </div>

      <div class="w-full border-t-2 pt-3 border-gray-400">
        <p class="text-xs text-center text-gray-400">&copy; SPYRO 2023. All rights reserved.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FooterSection'
}
</script>

<style scoped>
.social {
  color: var(--primary-color);
  font-size: 22px;
  padding: 5px;
}

@media (max-width: 700px) {
  .change-font {
    font-size: calc(2px + 0.2vw);
  }
}
</style>
