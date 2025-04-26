<script setup>
import { ref } from 'vue';


const mayorEdad = ref(false)

</script>

<template>


<div>

  <p v-if="mayorEdad"> tienes 18</p>
  <p v-else> no tienes 18</p>

</div>

</template>

<style>

</style>
