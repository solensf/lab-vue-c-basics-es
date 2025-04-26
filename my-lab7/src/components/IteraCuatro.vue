<script setup>

const publicaciones = [
{
title: "CSS",
description: "How to give style",
content:"CSS exercises, CSS theory"
},
{
title: "JavaScript",
description: "How to use logic",
content:"JavaScript exercises, JavaScript theory"
},
{
title: "Vue",
description: "How to use Framework",
content:"Vue exercises, Vue theory"
}
]
</script>

<template>

<ul class="product-list">
  <li v-for="temas in publicaciones" :key="temas.title">
    <h1>{{ temas.title }}</h1>
    <h2>{{ temas.description }}</h2>
    <h3>{{ temas.content }}</h3>
  </li>
</ul>
</template>

<style>
.product-list {
  list-style: none;
}

</style>