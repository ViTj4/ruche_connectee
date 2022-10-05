<template>
  <div id="app">
    <NavbarComponent></NavbarComponent>
  </div>
</template>

<script>
import NavbarComponent from '../src/components/NavbarComponent.vue'

export default {
  name: 'App',
  components: {
    NavbarComponent
}
}
</script>

<style>
body
{
  margin:0 !important;
}
</style>
