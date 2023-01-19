<script>
import Navbar from "@/components/Navbar/Navbar.vue";

export default {
  name: "ContactView",
  components: {
    Navbar,
  },
};
</script>

<template>
  <div class="bg-[url('/src/components/Backgrounds/background-home.svg')] bg-no-repeat bg-cover h-screen">
    <Navbar />
    <h1>Contact</h1>
  </div>
</template>
