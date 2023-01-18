<script setup>
defineProps({
  text: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <button class="bg-[#2157F2]">{{ text }}</button>
</template>
