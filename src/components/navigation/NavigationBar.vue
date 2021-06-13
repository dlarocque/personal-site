<template>
  <v-app-bar dark fixed app>
    <div class="routebuttons">
      <router-link :to="{ path: '/', hash: '#home' }" class="routerlink"
        >Home</router-link
      >
      <router-link :to="{ path: '/', hash: '#about' }" class="routerlink"
        >About</router-link
      >
      <router-link :to="{ path: '/', hash: '#projects' }" class="routerlink"
        >Projects</router-link
      >
    </div>
    <div class="contactbuttons">
      <v-btn
        icon
        large
        right
        dense
        href="mailto:dlarocque.contact@gmail.com"
        class="contactbutton"
      >
        <v-icon>mdi-email</v-icon>
      </v-btn>
      <v-btn
        icon
        large
        href="https://www.linkedin.com/in/daniel-la-rocque-2b102b189/"
        target="_blank"
        class="contactbutton"
      >
        <v-icon>mdi-linkedin</v-icon>
      </v-btn>
      <v-btn
        icon
        large
        href="https://github.com/dlarocque"
        target="_blank"
        class="contactbutton"
      >
        <v-icon>mdi-github</v-icon>
      </v-btn>
    </div>
  </v-app-bar>
</template>

<script>
export default {
  name: "NavigationBar",
  components: {},
};
</script>
