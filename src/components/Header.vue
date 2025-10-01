<script lang="ts">
export default {
    name: 'Header',
}

</script>

<template>
  <header class="header">
    Minha Marca
    <div class="contatos">
        <a href="#hero">Linkedln</a>
        <a href="#features">Twitter</a>
        <a href="#cta">Github</a>
    </div>
  </header>
</template>

<style scoped>

header{
  align-items: center;;
  display: flex;
  height: 10%;
  background: #252525; 
  color: #f9f9f9; 
  position: fixed;
  top: 0;
  width: 100%;
  padding: 0 20px;
  z-index: 1000; 
}

header .contatos{
margin-left:auto;
display: flex;
gap: 20px;
}



</style>