<template>
  <section class="omOs">
    <NuxtImg src=".." alt="gaffel ske" />
    <div class="text-box">
      <h1>OM OS</h1>
      <p>
        Med vores app vælger du selv dine favoritretter, hvor ofte du vil have
        dem, og kan justere eller sætte på pause når som helst. Nyd lækker,
        varieret mad uden planlægning, stress eller tidsforbrug - alt kører helt
        af sig selv.
      </p>
    </div>
  </section>
</template>

<style scoped>
.omOs {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #638250;
  padding-top: 5rem;
  padding-bottom: 5rem;
  gap: 2rem;
}

.omOs img {
  max-width: 400px;
  width: 100%;
  height: auto;
  border-radius: 100px;
}

h1 {
  font-size: clamp(2rem, 5vw, 4rem);
  font-weight: bold;
}

.text-box {
  max-width: 30ch;
}

.text-box p {
  font-size: clamp(1rem, 2.5vw, 1.125rem);
}

@media (max-width: 800px) {
  .omOs {
    flex-direction: column;
    text-align: center;
  }

  .omOs img {
    max-width: 300px;
    width: 100%;
  }

  .text-box {
    max-width: 35ch;
  }
}
</style>
