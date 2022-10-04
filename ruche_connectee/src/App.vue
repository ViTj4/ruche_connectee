<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import NavbarVue from './components/Navbar.vue';
import CapteurComponent from './components/CapteurComponent.vue';
import CapteurGPSComponent from './components/CapteurGPSComponent.vue';
import MeteoComponent from './components/MeteoComponent.vue';
import OuvertureComponent from './components/OuvertureComponent.vue'
import TemperatureComponent from './components/TemperatureComponent.vue'
import Footer from './components/Footer.vue'
</script>

<template>

  <NavbarVue></NavbarVue>
  <TemperatureComponent></TemperatureComponent>
  <CapteurComposent></CapteurComposent>
  <CapteurGPSComponent></CapteurGPSComponent>
  <MeteoComponent></MeteoComponent>
  <OuvertureComponent></OuvertureComponent>
  <Footer></Footer>
  


</template>

<style scoped>
</style>
