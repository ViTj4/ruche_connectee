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
body
{
  margin:0 !important;
}
</style>
