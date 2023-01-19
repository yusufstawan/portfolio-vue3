<script>
import Navbar from "@/components/Navbar/Navbar.vue";
import ProjectCategory from "@/components/ProjectsComponents/ProjectCategory.vue";

export default {
  name: "ProjectsView",
  components: {
    Navbar,
    ProjectCategory,
  },
};
</script>

<template>
  <div class="bg-[url('/src/components/Backgrounds/background-home.svg')] bg-no-repeat bg-cover h-screen">
    <Navbar />
    <h1 class="text-center font-[500] text-[32px] leading-[136%] text-black">Project</h1>
    <div class="mt-[58px]">
      <ProjectCategory />
    </div>
  </div>
</template>
