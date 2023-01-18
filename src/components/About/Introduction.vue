<script setup>
import ButtonBlue from "../Button/ButtonBlue.vue";
</script>

<template>
  <div class="about-introduction">
    <h1 class="w-[422px] font-[700] text-[60px] text-[#393939] leading-[136%]">
      I'am
      <span class="text-[#2157F2]">Yusuf</span>
      Setiyawan
    </h1>
    <p class="w-[376px] font-[400] text-[20px] text-[#393939] leading-[150%]">Draft is a revolutionary mobile app built to help you manage your business easily and save your money.</p>

    <ButtonBlue :text="See Projects" />
  </div>
</template>

<style scoped>
.about-introduction {
  transform: matrix(1, 0, 0, -1, 0, 0);
}
</style>
