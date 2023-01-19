<script>
import NavbarLogo from "./NavbarLogo.vue";
import NavbarLink from "./NavbarLink.vue";
import NavbarTheme from "./NavbarTheme.vue";

export default {
  name: "Navbar",
  components: {
    NavbarLogo,
    NavbarLink,
    NavbarTheme,
  },
};
</script>

<template>
  <header class="flex justify-between items-center h-[79px] w-[1362px]">
    <NavbarLogo />
    <div class="flex justify-between">
      <NavbarLink />
      <NavbarTheme />
    </div>
  </header>
</template>
