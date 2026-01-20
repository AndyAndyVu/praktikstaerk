<template>
  <section class="layout">
    <div class="Forside">
      <NuxtImg src="/img/HAPS-logo.png" class="logo" />
      <div class="text-forside">
        <p>simpelt, nemt og hver uge</p>
        <p>
          bestil fra dine yndlings restauranter, på et fast månedligt rul hvor
          og hvornår du har lyst
        </p>
      </div>
      <div class="knapper">
        <Btn label="START DIT ABONNOMENT" to="#" />
        <Btn label="SE RESTURANTER" to="#" />
      </div>
    </div>
    <NuxtImg src="/img/HAPS-mad.png" class="grid-billede" />
  </section>
</template>

<style scoped>
.layout {
  display: flex;
}
.Forside {
  background-color: #638250;
  padding: 5rem 5rem;
  text-align: center;
  width: 60%;
}
.text-forside p {
  font-size: 1.2rem;
}
.logo {
  width: 400px;
}
.grid-billede {
  width: 30%;
}

@media (max-width: 800px) {
  .layout {
    flex-direction: column;
    align-items: center;
  }

  .Forside {
    width: 100%;
    padding: 3rem 1.5rem;
  }

  .logo {
    width: 250px;
  }

  .text-forside p {
    font-size: 1rem;
  }

  .knapper {
    display: flex;
    justify-content: center;
    margin-top: 2rem;
    font-size: 0.8rem;
  }

  .grid-billede {
    display: none;
  }
}
</style>
