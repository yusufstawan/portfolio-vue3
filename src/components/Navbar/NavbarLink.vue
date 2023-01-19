<script>
import { RouterLink } from "vue-router";

export default {
  name: "NavbarLink",
  data() {
    return {
      links: [
        {
          name: "Home",
          link: "/",
        },
        {
          name: "Projects",
          link: "/projects",
        },
        {
          name: "About",
          link: "/about",
        },
        {
          name: "Contact",
          link: "/contact",
        },
      ],
    };
  },
  components: { RouterLink },
};
</script>

<template>
  <div class="flex items-center">
    <nav>
      <ul class="flex">
        <li class="mr-[58px]" v-for="link in links" :key="link.name">
          <RouterLink :to="link.link" class="font-[400] text-[16px] leading-[19px] text-[#393939]">{{ link.name }}</RouterLink>
        </li>
      </ul>
    </nav>
  </div>
</template>
