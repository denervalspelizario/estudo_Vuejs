<!-- Script  -->
<script setup>
  // Variavel
  let exibir = true;
 
  // de acordo com o valor sera exibido pelo v-if
  let media = 8;
</script>

<!-- HTML -->

<template>
  <!--  se exibir for true exibir se estiver false vai ocultar  -->
  <h1 v-if="exibir">Hello World!!</h1>

  <!-- atencao as condicoes do v-if -->
  <p v-if="media >= 7" >Aprovado(a)</p>
  <p v-else-if="media >= 5">Em exame</p>
  <p v-else>Reprovado(a)</p>
</template>
