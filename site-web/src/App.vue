<template>
  <div id="app">
    <header-nav></header-nav>
    <home-nav></home-nav>
    <about></about>
  </div>
</template>

<script>
import HeaderNav from './components/HeaderNav'
import HomeNav from './components/HomeNav'
import About from './components/About'

export default {
  components: {
    HeaderNav,
    HomeNav,
    About,
  }
}
</script>

<style>
html {
  height: 100%;
  width: 100%;
}

body {
  height: 100%;
  width: 100%;
}

#app {
  color: #2c3e50;
  height: 100%;
  width: 100%;
  position: absolute;
  top: 0;
  left: 0;
}

#app a {
  color: #42b983;
  text-decoration: none;
}
</style>
