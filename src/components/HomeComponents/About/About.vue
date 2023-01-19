<script>
import Photos from "./Photos.vue";
import Introduction from "./Introduction.vue";

export default {
  name: "About",
  components: {
    Photos,
    Introduction,
  },
};
</script>

<template>
  <div class="absolute w-[1158px] h-[507px] top-[250px] about-background">
    <div class="absolute top-[50px] left-[100px] flex justify-between items-center">
      <Photos class="mr-[76px]" />
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
