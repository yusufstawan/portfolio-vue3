<script setup>
import Photos from "./Photos.vue";
import Introduction from "./Introduction.vue";
</script>

<template>
  <div class="absolute w-[1158px] h-[507px] top-[300px] about-background">
    <div class="flex justify-center items-center">
      <Photos />
      <Introduction />
    </div>
  </div>
</template>

<style scoped>
.about-background {
  background: linear-gradient(146.64deg, rgba(255, 255, 255, 0.5) -6.76%, rgba(0, 71, 255, 0.05) 102.96%);
  backdrop-filter: blur(10px);
  border-radius: 0px 200px;
  box-sizing: border-box;
  transform: matrix(1, 0, 0, -1, 0, 0);
}
</style>
