<template>
  <div id="app">
    <header-nav></header-nav>
    <home-nav></home-nav>
    <about></about>
    <evenements></evenements>
    <transmission></transmission>
  </div>
</template>

<script>
import HeaderNav from './components/HeaderNav'
import HomeNav from './components/HomeNav'
import About from './components/About'
import Evenements from './components/Evenements'
import Transmission from './components/Transmission'

export default {
  components: {
    HeaderNav,
    HomeNav,
    About,
    Evenements,
    Transmission,
  }
}
</script>

<style>
html {
  height: 100%;
  width: 100%;
}

body{
    overflow: hidden;
    height: 100%;
    width: 100%;
    top:0px;
    left: 0px;
    margin: 0;
    padding: 0;

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
