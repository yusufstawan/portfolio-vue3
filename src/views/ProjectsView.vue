<script>
import Navbar from "../components/Navbar/Navbar.vue";
import ProjectCategory from "../components/ProjectsComponents/ProjectCategory.vue";
import ProjectCard from "../components/ProjectsComponents/ProjectCard.vue";

export default {
  name: "ProjectsView",
  components: {
    Navbar,
    ProjectCategory,
    ProjectCard,
  },
  data() {
    return {
      projectCategory: [
        {
          id: 1,
          name: "Story",
          active: false,
        },
        {
          id: 2,
          name: "Post",
          active: false,
        },
        {
          id: 3,
          name: "Banner",
          active: false,
        },
        {
          id: 4,
          name: "Trailer",
          active: true,
        },
        {
          id: 5,
          name: "Design",
          active: false,
        },
        {
          id: 6,
          name: "Motion",
          active: false,
        },
      ],
    };
  },
};
</script>

<template>
  <div class="bg-[url('/src/components/Backgrounds/background-home.svg')] bg-no-repeat bg-cover h-screen">
    <Navbar />
    <h1 class="text-center font-[500] text-[30px] leading-[136%] text-black">Projects</h1>

    <div class="mt-[58px] flex justify-center">
      <div class="mr-[41px]" v-for="category in projectCategory" :key="category.id">
        <ProjectCategory :category="category.name" />
      </div>
    </div>

    <div class="mt-[61px]">
      <ProjectCard />
    </div>
  </div>
</template>
