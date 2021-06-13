<template>
  <section id="gambot">
    <h2>Gambot</h2>
    <div class="description">
      <h3>Description</h3>
      <p>
        Gambot is a discord bot that <b>tracks users activity</b> in the discord
        servers that it is connected to, and awards them "gold" accordingly.
        With this earned gold, users can wager in a game of
        <b>deathroll</b> against another played in the server.<br /><br />
        The bot was written in <b>Python</b> using the discord.py API, and
        stores the data it collects on users in a <b>PostgreSQL</b> database.
        Gambot was written to be a private discord bot, meaning that users who
        want the bot on their own discord server must set up and run the bot
        themselves. I have tried making the process of setting up the bot as
        quick as possible.
      </p>
    </div>
    <div class="background">
      <h3>Background</h3>
      <p>
        I've always wanted to create something that my friends could use and
        give me feedback on, but never had any ideas on what to make. After my
        friends and I began using Discord as a means of hanging out together
        during the lockdowns, I figured a discord bot would get some use.
        Despite not having any knowledge on Python, Databases, or API's, I
        managed to pull something together.
      </p>
    </div>
    <a href="https://github.com/dlarocque/gambot" target="_blank"
      >Source Code</a
    >
    <br />
    <a
      href="https://github.com/dlarocque/gambot/blob/master/README.md"
      target="_blank"
      >More Information</a
    >
    <br />
  </section>
</template>

<script>
export default {
  name: "AlgorithmVisualizer",
};
</script>

<style>
@import "../../assets/css/styles.css";
</style>
