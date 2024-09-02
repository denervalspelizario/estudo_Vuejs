<!-- Script  -->
<script setup>
   // Array/Vetor
   let nomes = ['Alice', 'Bruna', 'Caio', 'Daniel', 'Ellen']
</script>

<!-- HTML -->
<template>
  <!-- gerando um laco for nomes repassa para nome que imprime nome de 1 em 1 -->
  <ul>
    <li v-for="nome in nomes">{{ nome }}</li>
  </ul>

</template>