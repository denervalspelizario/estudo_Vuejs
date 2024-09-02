<!-- Script  -->
<script setup>
  //importar o ref
  import { ref } from 'vue';

   // Variavel
   let texto = ref('');
</script>

<!-- HTML -->
<template>
  <input type="text" v-model="texto">
  <p>{{ texto }}</p>
</template>