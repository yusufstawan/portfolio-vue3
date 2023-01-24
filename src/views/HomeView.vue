<script>
import Navbar from "../components/Navbar/Navbar.vue";
import About from "../components/HomeComponents/About/About.vue";
import Apps from "../components/HomeComponents/Apps/Apps.vue";

export default {
  name: "HomeView",
  components: {
    Navbar,
    About,
    Apps,
  },
  data() {
    return {
      apps: [
        {
          id: "1",
          text: "Photoshop",
        },
        {
          id: "2",
          text: "After Effects",
        },
        {
          id: "3",
          text: "Illustrator",
        },
        {
          id: "4",
          text: "Figma",
        },
      ],
    };
  },
};
</script>

<template>
  <div class="bg-[url('/src/components/Backgrounds/background-home.svg')] bg-no-repeat bg-cover h-screen">
    <Navbar />
    <About />
  </div>
  <div v-for="app in apps" :key="app.id">
    <Apps :text="app.text" />
  </div>
</template>
