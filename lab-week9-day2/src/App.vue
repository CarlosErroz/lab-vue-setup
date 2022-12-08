<template>
  <h1>{{ titleArticle }}</h1>
  
  <Article />

  <Button />
  
</template>

<script setup>
import Article from "./components/Article.vue";
import Button from "./components/Button.vue";
import {ref} from 'vue';
const titleArticle = ref("Ejercicios Lab Week9-Day2");
</script>

<style>
</style>