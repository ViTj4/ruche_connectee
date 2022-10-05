<template>
  <div id="app">
    <AccueilComponent></AccueilComponent>
  </div>
</template>

<script>
import AccueilComponent from '../src/components/AccueilComponent.vue'

export default {
  name: 'App',
  components: {
    AccueilComponent
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
