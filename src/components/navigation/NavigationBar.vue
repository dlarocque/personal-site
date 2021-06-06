<template>
  <v-app-bar dark fixed app>
    <nav>
      <router-link to="/" class="routerlink">Home</router-link>
      <router-link to="/about" class="routerlink">About</router-link>
      <router-link to="/projects" class="routerlink">Projects</router-link>
      <router-link to="/contact" class="routerlink">Contact</router-link>
    </nav>
  </v-app-bar>
</template>

<script>
export default {
  name: "NavigationBar",
  components: {},
};
</script>

<style scoped>
nav {
  margin-left: auto;
  margin-right: auto;
}

.routerlink:hover {
  color: lightslategray;
}

nav .routerlink.active {
  color: darkgray;
}

.routerlink {
  color: whitesmoke;
  text-decoration: none;
  margin-left: 12px;
  margin-right: 12px;
}
</style>
