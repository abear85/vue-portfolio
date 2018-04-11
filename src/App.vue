<template>
  <div id="app">
    <header>
      <!-- LOGO WILL GO HERE -->
      <nav>
        <router-link to="/">Home</router-link>
        <router-link to="about">About</router-link>
      </nav>
    </header>
    <img src="./assets/logo.png">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="scss">
@import './assets/scss/main.scss';
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
