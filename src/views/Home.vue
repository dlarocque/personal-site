<template>
  <section id="home">
    <h1>Daniel La Rocque</h1>
    <h3>Undergraduate Computer Science Student</h3>
    <p>
      This is where you can find all of the projects I've worked on as well as
      some information about me! The projects I have are still limited, but I
      hope that one day this site will be full of interesting and diverse
      projects.
    </p>
  </section>
</template>

<script>
export default {
  name: "Home",
  components: {},
};
</script>

<style>
section {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  width: 60%;
  height: 80vh;
  background-color: white;
  margin-left: auto;
  margin-right: auto;
}

h1 {
  font-size: 40px;
  margin-bottom: 15px;
}

h3 {
  margin-bottom: 30px;
}

p {
  margin-left: auto;
  margin-right: auto;
  width: 80vh;
}

.home {
  text-align: center;
}
</style>
