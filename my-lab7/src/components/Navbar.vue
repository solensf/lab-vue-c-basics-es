<script setup>
import { ref } from 'vue';

const nombre = ref ("")
const apellido = ref ("")


function nombreCompleto() {
  return nombre.value + " " + apellido.value;
}

</script>

<template>
<input v-model="nombre">
<input v-model="apellido">
  <h1>{{ nombreCompleto() }}</h1>

</template>

<style>

</style>
