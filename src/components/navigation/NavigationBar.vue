<template>
  <v-app-bar dark fixed app>
    <nav>
      <router-link :to="{ path: '/', hash: '#home' }" class="routerlink"
        >Home</router-link
      >
      <router-link :to="{ path: '/', hash: '#about' }" class="routerlink"
        >About</router-link
      >
      <router-link :to="{ path: '/', hash: '#projects' }" class="routerlink"
        >Projects</router-link
      >
      <router-link :to="{ path: '/', hash: '#contact' }" class="routerlink"
        >Contact</router-link
      >
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
  font-size: 18px;
  margin-left: 12px;
  margin-right: 12px;
}
</style>
