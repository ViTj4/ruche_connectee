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
    <div class="brown">
    <div class="centerlogo">
        <img class="logo" src="../assets/pictures/logo_blanc.png" alt="">
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
    padding:1em;
    font-size: xx-large;
    color: #6E573F;
    font: 900;
    text-shadow: 2em;
    font-family:fantasy;
    


 }

  .navbar-item:hover {
    background-color: #6E573F !important;
    color: #F89F2B !important;
    font-style: italic;
    text-shadow: 2em;
    font-family:fantasy;
    
 }

 .logo{
    z-index: 2;
 }
 
 .brown{
    background-color: #6E573F;

 }
 .centerlogo{
    margin-left: auto;
    margin-right:auto;
    width: 4%;
 }
</style>