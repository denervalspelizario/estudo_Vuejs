
<!-- Script -->
<script setup>

  // variaveis
  let nome = 'Alice';
  let idade = 25;
  let n1 = 10;
  let n2 = 15;
</script>

<!-- HTML -->
<template>
  <p>{{'Ola ' + nome  + ' voce tem ' + idade + ' anos de idade '}}</p>
  <p>{{ n1 + n2 }}</p>
</template>