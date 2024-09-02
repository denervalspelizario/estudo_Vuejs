<!-- Script  -->
<script setup>
   // Variavel
   let validacao = true;
</script>

<!-- CSS -->
<style>
  .ok{color: green;} /* classe css ok */

  .falha{color: red} /* classe css falha */
</style>

<!-- HTML -->
<template>
  <p :class="validacao ? 'ok' : 'falha'">Utilizando a diretiva class</p>
</template>