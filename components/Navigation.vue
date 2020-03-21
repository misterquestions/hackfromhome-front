<template>
  <div class="navigation">
    <nuxt-link to="home" class="link">HOME</nuxt-link>
    <nuxt-link to="index" class="link">LOG IN</nuxt-link>
    <nuxt-link to="about" class="link">KNOW ABOUT THE PROJECT</nuxt-link>
    <nuxt-link to="challenges" class="link">CHALLENGES</nuxt-link>
  </div>
</template>

<style>
.navigation {
  padding-top: 4em;
  margin-left: 20%;
  margin-bottom: 2em;
  position: relative;
  display: flex;
  justify-content: flex-start;
}

.link {
  padding: 0 3em;
  color: #adb5bd;
  transition: color 200ms ease-in-out;
}

.link:hover {
  text-decoration: none;
  color: black;
}

a.nuxt-link-active {
  color: black;
}

.download {
  margin-left: auto;
  margin-right: 2em;
  border-radius: 30px;
  padding: 0.6em 2em;
  background-color: black;
  color: white;
  font-size: 1.1em;
}
</style>
