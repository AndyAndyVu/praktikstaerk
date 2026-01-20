<template>
  <header class="header">
    <div class="logo">
      <NuxtLink to="/">
        <img src="/img/HAPS-logo.png" alt="HAPS logo" />
      </NuxtLink>
    </div>
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
          <NuxtLink to="Abboner">🔔 Abboner</NuxtLink>
        </li>
      </ul>
    </nav>

    <NuxtLink class="opret" to="/opret-bruger">
      <img src="/img/login-ikon.png" alt="" /> Opret bruger</NuxtLink
    >
  </header>
</template>

<style scoped>
.header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: #2e4e2d;
  padding: 1.5rem 3rem;
  list-style: none;
}

.logo img {
  max-width: 80px;
}

.nav-list {
  display: flex;
  gap: 4rem;
  list-style: none;
}

.nav-list a {
  color: white;
  text-decoration: none;
  font-size: 1.2rem;
}

.nav-list a:hover {
  text-decoration: underline;
}

.opret {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  padding: 1rem 1rem;
  border-radius: 25px;
  background-color: #dd9b21;
  color: black;
  font-weight: 600;
  text-decoration: none;
}

.opret img {
  width: 18px;
  height: 18px;
  position: relative;
  top: 2px;
}
</style>
