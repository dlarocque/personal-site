<template>
  <body>
    <section id="home">
      <h1>Welcome to my personal website!</h1>
      <p>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Deserunt
        soluta dolores veniam vel exercitationem laboriosam odit voluptatibus
        quisquam, repellat in similique laborum culpa expedita voluptatum
        numquam consequatur laudantium id dolore.
      </p>
    </section>
  </body>
</template>

<script>
export default {
  name: "Home",
  components: {},
};
</script>

<style>
body {
  width: 100%;
}

section {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  width: 100%;
  height: 80vh;
}

p {
  margin-left: auto;
  margin-right: auto;
  width: 100vh;
}

.home {
  text-align: center;
}
</style>
