<script>
export default {
  name: "ProjectCategory",
  props: {
    category: {
      type: String,
      default: "None",
    },
  },
};
</script>

<template>
  <button class="box-border w-[159px] h-[42px] bg-[#F8FAFF] border-[3px] border-[#A6BCFA] rounded-[67px]">
    <p class="font-[400] text-[20px] text-[#1F1F1F]">{{ category }}</p>
  </button>
</template>
