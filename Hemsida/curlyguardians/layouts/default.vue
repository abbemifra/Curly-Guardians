<template>
  <div class="">
    <NavBar />
    <nuxt></nuxt>
    <FootComp />
  </div>
</template>

<script>
import NavBar from "../components/NavBar.vue";
import FootComp from "~/components/FootComp.vue";
export default {
  data() {
    return {
      NavBar,
    };
  },
  components: { NavBar, FootComp },
};
</script>
