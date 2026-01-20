<script setup>
const cards = [
  {
    id: 1,
    title: "Gourmet Burgere",
    text: "Pakket med de lækreste ingredienser",
    image: "/img/burger.png",
  },
  {
    id: 2,
    title: "Juicy Wings",
    text: "Kyllingevinger med fantastiske sovser",
    image: "/img/wings.png",
  },
  {
    id: 3,
    title: "Frisk Sushi",
    text: "Lækker sushi med friske ingredienser",
    image: "/img/sushi.png",
  },
];
</script>

<template>
  <section class="cards">
    <article v-for="card in cards" :key="card.id" class="card">
      <img :src="card.image" class="card-img" alt="" />
      <h3>{{ card.title }}</h3>
      <p>{{ card.text }}</p>
    </article>
  </section>
</template>
