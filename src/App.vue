<template>
  <nav>
    <router-link to="/">Задание 1</router-link>
    <router-link to="/quest-two">Задание 2</router-link>
  </nav>
  <router-view />
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
nav a:first-child {
  margin-right: 5em;
}
a:hover {
  color: white;
  background: #42b983;
  padding: 10px 20px 10px 20px;
  border-radius: 30px;
  transition: 0.5s;
}
nav {
  padding: 30px;
  align-items: center;
  display: flex;
  justify-content: center;

  a {
    font-weight: bold;
    color: #2c3e50;
    text-decoration: none;
    transition: 0.5s;
    font-family: ALS Sector, serif;

    &.router-link-exact-active {
      color: white;
      background: #42b983;
      padding: 10px 20px 10px 20px;
      border-radius: 30px;
      text-decoration: none;
    }
  }
}
</style>
