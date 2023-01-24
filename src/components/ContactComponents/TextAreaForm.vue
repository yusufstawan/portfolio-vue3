<script>
export default {
  name: "TextAreaForm",
  props: {
    cols: {
      type: Number,
      default: 30,
    },
    rows: {
      type: Number,
      default: 10,
    },
    placeholder: {
      type: String,
      default: "",
    },
    modelValue: {
      type: String,
      default: "",
    },
  },
  emits: ["update:modelValue"],
};
</script>

<template>
  <textarea :cols="cols" :rows="rows" :placeholder="placeholder" :value="modelValue" @input="$emit('update:modelValue', $event.target.value)" class="bg-[#F5F5F5] rounded-[9px]"></textarea>
</template>
