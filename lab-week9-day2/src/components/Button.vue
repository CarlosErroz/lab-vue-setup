<template>
  <button class="button" @click="helloWorld">Click to Hello in console</button>
</template>

<script setup>
import {ref} from 'vue';
function helloWorld() {
    console.log("hello world");
}
</script>

<style>
.button {
    margin:10px;
}

</style>