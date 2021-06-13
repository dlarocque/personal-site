<template>
  <section id="projects">
    <h1>Projects</h1>
    <v-container>
      <v-row justify="center">
        <v-col md="4">
          <v-card>
            <v-img
              src="../assets/algorithmvisualizer/alg-1.png"
              class="img"
            ></v-img>
            <v-card-title primary-title
              >Sorting Algorithm Visualizer</v-card-title
            >
            <v-card-text
              >Application that allows users to visualize some of the most well
              known sorting algorithms at a chosen speed and input size.
            </v-card-text>
            <v-card-actions>
              <v-btn>
                <router-link
                  :to="{ path: '/', hash: '#gambot' }"
                  class="routerlink"
                  >Details</router-link
                ></v-btn
              >
              <v-btn
                ><a href="https://github.com/dlarocque/gambot" target="blank"
                  >Source Code</a
                ></v-btn
              >
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col md="4">
          <v-card>
            <v-img src="../assets/gambot/gambot.png" class="img"></v-img>
            <v-card-title primary-title>Gambot</v-card-title>
            <v-card-text
              >Discord bot that allows users to wager points earned through
              activity in a discord server in a "deathroll" game.
            </v-card-text>
            <v-card-actions>
              <v-btn>
                <router-link
                  :to="{ path: '/', hash: '#algorithm-visualizer' }"
                  class="routerlink"
                  >Details</router-link
                ></v-btn
              >
              <v-btn
                ><a
                  href="https://github.com/dlarocque/algorithm-visualizer"
                  target="blank"
                  >Source Code</a
                ></v-btn
              >
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<script>
export default {
  name: "Projects",
};
</script>
