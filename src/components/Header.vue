<script lang="ts">
export default {
  name: 'Header-component',
}
</script>

<template>
  <header class="header">
    Minha Marca
    <div class="contatos">
      <a href="https://www.linkedin.com/in/matheus-de-jesus-silva-94a9a7264/" target="_blank"
        >Linkedln</a
      >
      <a href="">Twitter</a>
      <a href="https://github.com/MathJesusDev">Github</a>
    </div>
  </header>
</template>

<style scoped>
header {
  align-items: center;
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

header .contatos {
  margin-left: auto;
  display: flex;
  gap: 20px;
}
</style>
