<script lang="ts">
export default {
  name: 'Hero-component',
}
</script>

<template>
  <div class="hero">
    <div class="container">
      <h1>Bem-vindo ao meu portfólio</h1>
      <p>
        Me chamo Matheus de Jesus, tenho 19 anos e atuo na área de manutenção e suporte de TI no
        Instituo Presbiteriano Mackenzie
      </p>
    </div>

    <div class="habilidades">cards de habilidades</div>
  </div>
</template>

<style scoped>
.hero {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
}

.habilidades {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 40px;
  width: 100vh;
}

.container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 40px;
  width: 100vh;
}

h1 {
  font-size: 3rem;
  margin-bottom: 20px;
  width: 100vh;
}

p {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 1.1rem;
}
</style>
