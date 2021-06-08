<template>
  <section id="about">
    <h1>About</h1>
    <p>
      Hey! I'm Daniel, a third year computer science undergraduate student at
      the University of Manitoba.<br /><br />
      Since I'm still only 19 years old, I don't really have much to say for
      myself! I grew up in
      <a
        href="https://static.wikia.nocookie.net/simpsons/images/0/0e/Winnipeg.jpg/revision/latest?cb=20120719011109"
        target="blank"
        >Winnipeg</a
      >
      , spent my time playing hockey and video games, while trying not to die
      from the
      <a
        href="https://www.cbc.ca/news/canada/manitoba/winnipeg-deep-freeze-as-cold-as-uninhabited-planet-1.2479967"
        target="blank"
        >brutal climate</a
      >. I fell into my passion of Computer Science in my first year of
      University, in my university's intro CS course. After spending two years
      learning the ropes in University, I'm now learning about the practical
      applications of my studies through my first summer internship at
      <a href="https://www.bell.ca/Mobility/Our_network" target="blank"
        >Bell Canada</a
      >
      in Montreal.<br /><br />
      Outside of working at my intership, I like working on some of my own
      <router-link :to="{ path: '/', hash: '#projects' }" class="routerlink"
        >personal projects</router-link
      >, or whatever I find interesting, really.<br /><br />
      If, for whatever reason, you're interested in knowing more about me,
      <router-link :to="{ path: '/', hash: '#contact' }" class="routerlink"
        >contact me!</router-link
      >
    </p>
  </section>
</template>

<script>
export default {
  name: "About",
  components: {},
};
</script>
