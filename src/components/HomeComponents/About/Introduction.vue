<script>
import ButtonBlue from "../../Button/ButtonBlue.vue";
import ButtonLight from "../../Button/ButtonLight.vue";

export default {
  name: "Introduction",
  components: {
    ButtonBlue,
    ButtonLight,
  },
};
</script>

<template>
  <div class="about-introduction">
    <h1 class="w-[448px] font-[700] text-[60px] text-[#393939] leading-[136%]">
      Hello,
      <span class="text-[#2157F2]">I’m</span>
      Yusuf Setiyawan
    </h1>
    <p class="w-[376px] font-[400] text-[20px] text-[#393939] leading-[150%] mt-[19px]">Draft is a revolutionary mobile app built to help you manage your business easily and save your money.</p>

    <div class="mt-[42px]">
      <ButtonBlue text="See Projects" to="/projects" class="mr-2" />
      <ButtonLight text="Download Resume" />
    </div>
  </div>
</template>

<style scoped>
.about-introduction {
  transform: matrix(1, 0, 0, -1, 0, 0);
}
</style>
