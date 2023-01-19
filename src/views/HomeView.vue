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
};
</script>

<template>
  <div class="bg-[url('/src/components/Backgrounds/background-home.svg')] bg-no-repeat bg-cover h-screen flex justify-center">
    <Navbar />
    <About />
    <Apps />
  </div>
</template>
