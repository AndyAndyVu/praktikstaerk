<template>
  <header>
    <nav aria-label="Hovednavigation">
      <ul class="nav-list">
        <li>
          <NuxtLink to="/menu">Menu</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/om-os">Om os</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/kontakt">Kontakt</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/login">Login/</NuxtLink>

          <NuxtLink to="/opret-bruger">Opret 👤</NuxtLink>
        </li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
.nav-list {
  display: flex;
  justify-content: flex-end;
  gap: 4rem;
  padding-right: 100px;
  background-color: green;
  padding: 2rem;
}

ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

a {
  color: white;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}
</style>
