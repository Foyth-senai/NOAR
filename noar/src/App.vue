<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
//import { IoPersonCircleOutline } from "oh-vue-icons/icons";
</script>

<template>
  <main class="flex-column">
    <div class="glass">
      <header id="cabecalho">
        <img src="../public/noar_pequena.png" alt="Logo">
      </header>

      <form action="" class="meio">
        <div class="container">
          <input required="" type="text" name="text" class="input">
          <label class="label">Insira seu CPF</label>
        </div>
        <div class="container">
          <input required="" type="password" name="text" class="input">
          <label class="label">Insira sua senha</label>
        </div>

        <button type="subimt" class="button"> Entrar </button>
        <a href="https://css.glass/">
          <p class="texto">Esqueceu sua senha?</p>
        </a>
      </form>

    </div>
  </main>
</template>

