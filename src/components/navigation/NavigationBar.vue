<template>
  <div class="navigationbar">
    <v-app-bar dark>
      <!-- v-app-bar-title text is truncated in 2.4.0, using span instead -->
      <span class="appbartitle">Daniel La Rocque</span>
      <v-spacer></v-spacer>
      <nav>
        <router-link to="/" class="routerlink">Home</router-link>
        <router-link to="/about" class="routerlink">About</router-link>
        <router-link to="/contact" class="routerlink">Contact</router-link>
      </nav>
    </v-app-bar>
  </div>
</template>

<script>
export default {
  name: "NavigationBar",
  components: {},
};
</script>

<style scoped>
.appbartitle {
  font-size: 20px;
}

.v-app-bar-title {
  color: whitesmoke;
}

.routerlink {
  color: whitesmoke;
  text-decoration: none;
  padding-right: 25px;
}
</style>
