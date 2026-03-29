<template>
  <div id="app">
    <navbar></navbar>
    <router-view />
  </div>
</template>

<script>
import Navbar from "@/components/AppNavbar.vue";
export default {
  name: "App",
  components: {
    Navbar,
  },
};
</script>

<style></style>
