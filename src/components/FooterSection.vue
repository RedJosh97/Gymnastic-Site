<template>
  <div class="relative">
    <img src="/public/image/Rectangle 49.png" />
    <div
      class="absolute top-0 left-0 px-20 pt-12 right-0 flex gap-9 flex-col justify-center items-center"
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
      <hr class="w-4/5" />
      <p class="text-xs -mt-7 text-gray-400">&copy; SPYRO 2023. All rights reserved.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FooterSection'
}
</script>

<style>
.social {
  color: var(--primary-color);
  font-size: 22px;
  padding: 5px;
}
</style>
