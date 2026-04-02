<template>
  <nav class="pure-menu pure-menu-horizontal">
    <div class="pure-menu-heading">Hacker News Clone</div>
    <ul class="pure-menu-list">
      <li class="pure-menu-item">
        <router-link to="/" class="pure-menu-link">Home</router-link>
      </li>
      <li class="pure-menu-item">
        <router-link to="/about" class="pure-menu-link">About</router-link>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "AppNavbar",
};
</script>

<style scoped>
nav {
  background: #ff6600;
  padding: 10px;
  margin-bottom: 20px;
}
.pure-menu-heading {
  color: white;
}
.pure-menu-link {
  color: white;
}
</style>