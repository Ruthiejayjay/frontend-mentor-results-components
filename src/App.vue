<template>
  <div id="app" class="flex flex-col justify-center items-center h-screen">
    <Cards />
    <div class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
      Coded by <a href="https://github.com/Ruthiejayjay">Ruth James</a>.
    </div>
  </div>
</template>

<script>
import Cards from "./components/Cards.vue"

export default {
  name: 'App',
  components: {
    Cards
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Hanken+Grotesk:ital,wght@0,200;0,300;1,100&display=swap');

#app {
  font-family: 'Hanken Grotesk', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.attribution {
  font-size: 11px;
  text-align: center;
  margin-top: 10px;
}

.attribution a {
  color: hsl(228, 45%, 44%);
}</style>
