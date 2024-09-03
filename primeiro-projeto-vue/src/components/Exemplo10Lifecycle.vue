<!-- Script  
  Lifecycle: São ações que podem acontecer em tres estapadas de componente
  - Antes da criação
  - Durante a criação
  - Após a criação
-->
<script setup>
   // Importações

import { onMounted, ref } from 'vue';

   // Variável de texto
   let texto = ref('Hello World!')

   // Lifecycle onMounted (função que troca valor da variavel texto depois de 3 segundo)
   onMounted(() => {
    setTimeout(() => {
      texto.value = 'Alterando texto'
    }, 3000)
   })
   
</script>


<!-- HTML -->
<template>
  <br>
  <br>
  <h1>{{ texto }}</h1>
</template>