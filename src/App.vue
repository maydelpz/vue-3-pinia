<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>



<template>
  <nav class="navbar bg-dark navbar-dark">
  <div class="container-fluid">
    <router-link
    class="navbar-brand" to="/">
      <img src="@/assets/logo.svg" alt="Logo" width="30" height="24" class="d-inline-block align-text-top">
      PokeApi
    </router-link>
    <div>
      <router-link class="btn btn-outline-primary m-2" to="/">Home</router-link>
      <router-link class="btn btn-outline-primary" to="/pokemons">Pokemons</router-link>
    </div>
  </div>
</nav>

  <div class="container text-center">
  <RouterView />
  </div>

</template>
