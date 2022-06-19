<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <GridLayout />
  </div>
</template>

<script>
import GridLayout from './components/GridLayout.vue';

export default {
  name: 'App',
  components: {
    GridLayout
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
