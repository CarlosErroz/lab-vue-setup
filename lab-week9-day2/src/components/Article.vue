<template>
  <article class="article">
    <img src="../assets/png-transparent-ironhack-hd-logo.png" alt="Imagen">
    <h2>Título</h2>
    <p>Cuerpo del artículo</p>
  </article>
</template>

<script setup>
</script>

<style>
.article {
  background-color: aqua;
  color:blue;
  width: 200px;
  padding:10px;
  display:flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  border-radius:10px;
}
.article img {
  max-width: 100%;
}

</style>