<script setup>
import { cards } from "~/data/cards";
</script>

<template>
  <main>
    <Navdesk />
    <forside />
    <omos />
    <Card v-for="card in cards" :key="card.id" v-bind="card" />
  </main>
</template>
