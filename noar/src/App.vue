<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
//import { IoPersonCircleOutline } from "oh-vue-icons/icons";
</script>

<template>
  <header id="cabecalho">
      <img src="../public/noar_pequena.png" alt="Logo">
  </header>
  <main class="flex-column">
    
    <input type="text" placeholder="Informe seu CPF ">
    <input type="password" placeholder="Insira sua senha">
  </main>

</template>

