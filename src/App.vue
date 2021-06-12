<template>
  <v-app>
    <v-main>
      <NavigationBar />
      <div class="content">
        <Home />
        <About />
        <Projects />
        <Contact />
      </div>
      <router-view />
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
