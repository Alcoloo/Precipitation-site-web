<template>
  <div id="app">
    <header-nav></header-nav>
    <div class="container">
        <component :is="currentView" transition="fade" transition-mode="out-in" keep-alive></component>
          <!-- component changes when vm.currentView changes! -->
        </component>
    </div>
  </div>
</template>

<script>
import HeaderNav from './components/HeaderNav'
import HomeNav from './components/HomeNav'
import About from './components/About'
import Evenements from './components/Evenements'
import Transmission from './components/Transmission'
import Mecenat from './components/Mecenat.vue'
import Contact from './components/Contact.vue'
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
    'home' : HomeNav,
    'about' : About,
    'event' : Evenements,
    'transmission' : Transmission,
    'mecenat' : Mecenat,
    'contact' : Contact
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

.container{
    position:fixed;
    width: 100%;
    min-height: 900px;
    height: 100vh;
    z-index: -1;
    -webkit-perspective:100px;
    -webkit-perspective-origin:50% 50%;
}
.fade-transition {
  transition: opacity 0.2s ease;
}

.fade-enter, .fade-leave {
  opacity: 0;
}

#app a {
  color: #42b983;
  text-decoration: none;
}
</style>
