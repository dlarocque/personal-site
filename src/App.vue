<template>
  <v-app>
    <v-main>
      <NavigationBar />
      <div class="content">
        <Home />
        <About />
        <Projects />
        <AlgorithmVisualizer />
        <Gambot />
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
import AlgorithmVisualizer from "./views/projects/AlgorithmVisualizer.vue";
import Gambot from "./views/projects/Gambot.vue";

export default {
  name: "App",
  components: {
    NavigationBar,
    Home,
    About,
    Projects,
    AlgorithmVisualizer,
    Gambot,
  },
  data: () => ({
    //
  }),
};
</script>
