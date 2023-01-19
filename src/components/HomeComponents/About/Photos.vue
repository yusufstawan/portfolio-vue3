<script>
export default {
  name: "Photos",
};
</script>

<template>
  <img src="@/assets/images/profile.jpg" alt="Photos Profile" class="rounded-[334px] w-[401px] h-[401px] border-[25px] border-solid border-[#FFFFFF] about-photos" />
</template>

<style scoped>
.about-photos {
  transform: matrix(1, 0, 0, -1, 0, 0);
}
</style>
