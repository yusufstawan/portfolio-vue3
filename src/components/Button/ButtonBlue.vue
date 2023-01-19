<script>
import { RouterLink } from "vue-router";

export default {
  name: "ButtonBlue",
  props: {
    text: {
      type: String,
      default: "Button",
    },
    to: {
      type: String,
      default: "/",
    },
  },
  components: { RouterLink },
};
</script>

<template>
  <RouterLink :to="to">
    <button class="bg-[#2157F2] w-[200px] h-[54px] rounded-[20px] text-white">
      {{ text }}
    </button>
  </RouterLink>
</template>
