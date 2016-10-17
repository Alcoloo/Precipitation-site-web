<template>
  <div id="app">
    <header-nav></header-nav>
    <home-nav v-if = "currentView == 'home'"></home-nav>
    <about v-if = "currentView == 'about'"></about>
    <evenements v-if = "currentView == 'event'"></evenements>
    <transmission v-if = "currentView == 'transmission'"></transmission>
    <mecenat v-if = "currentView == 'mecenat'"></mecenat>
  </div>
</template>

<script>
import HeaderNav from './components/HeaderNav'
import HomeNav from './components/HomeNav'
import About from './components/About'
import Evenements from './components/Evenements'
import Transmission from './components/Transmission'
import Mecenat from './components/Mecenat.vue'

export default {
  data () {
    return {
      // note: changing this line won't causes changes
      // with hot-reload because the reloaded component
      // preserves its current state and we are modifying
      // its initial state.
      currentView : 'home'
    }
  },
  components: {
    HeaderNav,
    HomeNav,
    About,
    Evenements,
    Transmission,
    Mecenat,
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
