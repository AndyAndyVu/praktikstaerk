<script setup>
defineProps({
  title: String,
  text: String,
  image: String,
});
</script>

<template>
  <article class="card">
    <NuxtImg :src="image" class="card-img" alt="" />
    <h3>{{ title }}</h3>
    <p>{{ text }}</p>
  </article>
</template>
