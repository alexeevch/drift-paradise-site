<template id="nav">
  <nav>
    <router-link to="/">Главная</router-link>
    <router-link to="/">Тюнинг</router-link>
    <router-link to="/">Как играть</router-link>
    <router-link to="/about">Донат</router-link>
  </nav>
</template>

<style scoped>
nav {
  display: flex;
  flex-direction: column;
  justify-content: center;
  gap: 32px;
  padding: 4rem;
  height: 100vh;
  text-transform: uppercase;
  width: 20%;
}

a {
  font-size: 2vw;
}
</style>
