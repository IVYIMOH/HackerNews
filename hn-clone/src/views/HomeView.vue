<template>
  <div class="home">
    <h1>Hacker News Stories</h1>
    <HomePage />
  </div>
</template>

<script>
import HomePage from "@/components/HomePage.vue";

export default {
  name: "HomeView",
  components: {
    HomePage,
  },
};
</script>