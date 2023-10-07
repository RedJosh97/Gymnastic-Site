<template>
  <div class="bg-primary-color items-center flex justify-between gap-4 px-20 pt-24 pb-6">
    <div class="flex flex-col gap-8">
      <p class="text-white text-4xl font-bold leading-10 max-w-md">
        Download the most loved fitness app
      </p>
      <p class="text-white font-medium text-base">
        Start your fitness journey with us. Join the cult!
      </p>
      <div class="flex gap-4 items-center">
        <img src="/public/image/image 13.png" class="andriod" />
        <img src="/public/image/image 14.png" class="andriod" />
      </div>
    </div>
    <div class="flex item-center gap-5 relative">
      <img
        src="/public/image/iPhone 13 Pro.png"
        class="image-large absolute -bottom-7 left-24 right-0 w-56"
      />
      <img src="/public/image/iPhone 13 Pro.png" class="image-small" />
      <img src="/public/image/iPhone 13 Pro.png" class="image-small" />
    </div>
  </div>
</template>

<script>
export default {
  name: 'DownloadPlatform'
}
</script>

<style scoped>
.andriod {
  width: 130px;
}

.image-small {
  height: 320px;
  width: 190px;
}
</style>
