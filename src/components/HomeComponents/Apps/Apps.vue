<script>
export default {
  name: "Apps",
  props: {
    text: {
      type: String,
      default: "Apps",
    },
  },
};
</script>

<template>
  <div class="absolute bottom-[50px]">
    <div class="absolute top-[-50%] left-[25%] border-[10px] border-solid border-white rounded-full">
      <img src="@/assets/images/apps.png" alt="Apps Logo" class="w-[55px] h-[55px] bg-white" />
    </div>
    <div class="w-[161px] h-[91px] bg-[#A6BCFA] rounded-[24px] shadow-md">
      <p class="font-[600] text-[20px] leading-[136%] text-[#FFFF] text-center">{{ text }}</p>
    </div>
  </div>
</template>
