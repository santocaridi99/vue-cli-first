<template>
  <div id="app">
    <Title></Title>
    <jumbotron></jumbotron>
  </div>
</template>

<script>
import Title from "./components/Title.vue"
import jumbotron from "./components/jumbotron.vue"

export default {
  name: 'App',
  components: {
    Title,
    jumbotron
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
