<template>
  <section id="projects">
    <h1>Projects</h1>
    <algorithm-visualizer />
  </section>
</template>

<script>
import AlgorithmVisualizer from "../components/projects/AlgorithmVisualizer.vue";

export default {
  name: "Projects",
  components: { AlgorithmVisualizer },
};
</script>

<style>
.projects {
  text-align: center;
  height: 100%;
  width: 100%;
}

h1 {
  margin-bottom: 10vh;
}
</style>
