<script setup>


</script>

<template>
<nav class="navbar" role="navigation" aria-label="main navigation" >
  <div class="center-navbar">
    <div id="navbarBasicExample" class="navbar-menu" >
        <div class="navbar-start">
            <a class="navbar-item">
                Capteur Sonore
            </a>
            <a class="navbar-item">
                Température
            </a>
            <a class="navbar-item">
                Vérifier les ouvertures
            </a>
            <a class="navbar-item">
                Météo
            </a>
        </div>
    </div>
    </div>
</nav>

</template>

<style>
 .navbar{
   background-color:  #F89F2B;
 }
 .center-navbar{
    margin-left: auto;
    margin-right: auto;

 }
 .navbar-item{
    font-size: xx-large;
    color: #6E573F;
    font: 900;
    font-style: italic;


 }

  .navbar-item :hover {
    background-color: #6E573F;
    
    color: #F89F2B;
    
    text-decoration: underline;
    
 }
</style>