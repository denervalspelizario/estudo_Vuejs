<!-- Script  -->
<script setup>
   //Função
   function mensagem()
   {
      alert('Executando a função')
   }
</script>


<!-- HTML -->
<template>
  <br><br>
  <!--  so vai validar se usuario digitar enter 
        ou seja o @keyup so ativa quando digita uma tecla enter tab aqui vc
        escolher -->
  <input type="text" @keyup.enter="mensagem">
</template>