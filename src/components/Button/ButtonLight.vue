<script>
export default {
  name: "ButtonLight",
  props: {
    text: {
      type: String,
      default: "Button",
    },
  },
};
</script>

<template>
  <button class="bg-[#DCE6FF] w-[200px] h-[54px] rounded-[20px]">
    {{ text }}
  </button>
</template>
