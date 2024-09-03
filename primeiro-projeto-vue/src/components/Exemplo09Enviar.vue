<!-- Script  -->
<script setup>
   // Função para validar formulário
   function validarFormulario(event)
   {  
      alert('Formulário enviado!')

      event.preventDefault();
   }
</script>


<!-- HTML -->
<template>
  <br>
  <br>
  <br>
  <form action="www.globo.com" @submit="validarFormulario">
    <input type="submit" value="Enviar Formulario">
  </form>
</template>