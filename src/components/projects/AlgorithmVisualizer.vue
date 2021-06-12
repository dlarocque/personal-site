<template>
  <div class="algorithm-visualizer">
    <h2>Sorting Algorithm Visualizer</h2>
    <div class="description">
      <h3>Description</h3>
      <p>
        This application allows users to visualize several of the most popular
        sorting algorithms. The visualizations of the sorting algorithms are
        done on randomly generated arrays of a <b>size of the users choice</b>,
        and at a <b>speed of their choice.</b><br /><br />
        The <b>performance</b> of the sorting algorithm can also be seen by
        looking at the <b>index comparisons and swaps</b>, as well as the total
        visualization time.
      </p>
    </div>
    <div class="background">
      <h3>Background</h3>
      <p>
        This is the first decently sized personal project I've ever made. I made
        it in the summer of my freshman year of university, and was inspired by
        a YouTube video to try making these visualizations on my own. This is
        the first decently sized personal project I've ever made. I made it in
        the summer of my freshman year of university, and was inspired by a
        YouTube video to try making these visualizations on my own.
      </p>
    </div>
    <a href="https://github.com/dlarocque/algorithm-visualizer" target="blank"
      >Source Code</a
    >
    <br />
    <a
      href="https://github.com/dlarocque/algorithm-visualizer/blob/master/README.md"
      target="blank"
      >More Information</a
    >
    <br />
    <iframe
      width="560"
      height="315"
      src="https://www.youtube.com/embed/WDOpFcnzuaQ?start=8"
      title="YouTube video player"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen
    ></iframe
    >>
  </div>
</template>

<script>
export default {
  name: "AlgorithmVisualizer",
};
</script>

<style>
@import "../../assets/css/styles.css";
</style>
