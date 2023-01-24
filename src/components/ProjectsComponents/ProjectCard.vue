<script>
export default {
  name: "ProjectCard",
  props: {
    title: {
      type: String,
    },
    image: {
      type: String,
    },
    link: {
      type: String,
    },
  },
};
</script>

<template>
  <div class="w-[270px] h-[394px] rounded-[26px] bg-slate-400 relative">
    <img src="@/assets/project/1.png" alt="project-images" class="" />
    <div class="w-[270px] h-[154px] bg-[#F9F9FC] rounded-b-[26px] absolute top-[61%]"></div>
  </div>
</template>
