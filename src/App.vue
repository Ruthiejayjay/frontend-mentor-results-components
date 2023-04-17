<template>
  <div id="app" class="flex justify-center items-center h-screen">
    <Button />
    <Cards />
  </div>
</template>

<script>
import Button from "./components/Button.vue"
import Cards from "./components/Cards.vue"

export default {
  name: 'App',
  components: {
    Button,
    Cards
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
