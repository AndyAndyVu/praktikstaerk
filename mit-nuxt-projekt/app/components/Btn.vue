<template>
  <NuxtLink :to="to" class="knap">
    <span v-html="label"></span>
  </NuxtLink>
</template>

<script setup>
defineProps({
  label: String,
  to: String,
});
</script>

<!-- defineProps anvendes for at gøre knappen genbrugelig.
label bestemmer teksten i knappen,
to angiver hvilken side knappen linker til. -->

<style scoped>
.knap {
  text-align: center;
  display: inline-block;
  padding: 1rem 1rem;
  border-radius: 1.5rem;
  background-color: #ffcc52;
  margin-right: 2rem;
  color: black;
  text-decoration: none;
  font-weight: bold;
}
</style>
