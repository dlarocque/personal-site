<template>
  <v-app>
    <v-main class="vmain">
      <NavigationBar />
      <Home />
      <About />
      <Projects />
      <Contact />
      <transition name="smooth">
        <router-view />
      </transition>
    </v-main>
  </v-app>
</template>

<script>
import NavigationBar from "./components/navigation/NavigationBar.vue";
import Home from "./views/Home.vue";
import About from "./views/About.vue";
import Projects from "./views/Projects.vue";
import Contact from "./views/Contact.vue";

export default {
  name: "App",
  components: { NavigationBar, Home, About, Projects, Contact },
  data: () => ({
    //
  }),
};
</script>
