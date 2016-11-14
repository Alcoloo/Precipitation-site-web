<template>
  <div id= "header">
    <nav>
      <ul>
        <li id ="lihome" v-bind:class="{active:isHome}"><button id="homeButton" v-on:click="switchView('home')">ACCUEIL</button></li>
        <li id ="liabout" v-bind:class="{active:isAbout}"><button id="aboutButton" v-on:click="switchView('about')">QUI SOMMES NOUS ?</button></li>
        <li id ="lievent" v-bind:class="{active:isEvent}"><button id="eventButton"  v-on:click="switchView('event')">EVÈNEMENTS</button></li>
        <li id ="litransmission" v-bind:class="{active:isTransmission}"><button id="transmissionButton"  v-on:click="switchView('transmission')">TRANSMISSION</button></li>
        <li id ="limecenat" v-bind:class="{active:isMecenat}"><button id="mecenatButton"  v-on:click="switchView('mecenat')">MÉCENAT</button></li>
        <li id ="licontact" v-bind:class="{active:isContact}"><button id="contactButton"  v-on:click="switchView('contact')">CONTACT</button></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  data () {
    return {
      // note: changing this line won't causes changes
      // with hot-reload because the reloaded component
      // preserves its current state and we are modifying
      // its initial state.
      lastViewClicked : 'home',
    }
  },
  computed:{
    isHome(){
      if(this.lastViewClicked == 'home')return true
      else return false
    },
    isAbout(){
      if(this.lastViewClicked == 'about')return true
      else return false
    },
    isEvent(){
      if(this.lastViewClicked == 'event')return true
      else return false
    },
    isTransmission(){
      if(this.lastViewClicked == 'transmission')return true
      else return false
    },
    isMecenat(){
      if(this.lastViewClicked == 'mecenat')return true
      else return false
    },
    isContact(){
      if(this.lastViewClicked == 'contact')return true
      else return false
    }
  },
  methods:{
    switchView(pTarget){
      this.$parent.currentView = pTarget
      this.lastViewClicked = pTarget
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@font-face {
    font-family: "futura-light";
    src: url('../assets/Futura_Std/FuturaStd-Light.otf') ;
}

*
{
  margin: 0;
  padding: 0;
}

button
{
  font-family: "futura-light";
  border: none;
  background: none;
  outline: none;
  font-size: larger;
}

 li button {
      text-decoration: none;
      color: white;
    }

    li button:hover {
      color: #333;
    }

    li.active button {
      font-weight:bold;
      color: #e08ba2;
    }

#header
{
  background: rgb(166, 43, 72);
  width: 100%;
  padding: 1px 0;
  color: white;
  text-transform: uppercase;
  text-align: center;
}

a
{
  text-decoration: none;
  color: inherit;
}

nav ul
{
  background-color: rgb(166, 43, 72);
  overflow: hidden;
  color: white;
  text-align: center;
  transition: 0.4s;
}

nav ul li
{
  display: inline-block;
  padding: 20px;
  font-size: 15px;
}

nav ul li:hover
{
  background-color: rgb(166, 43, 72);
  color:#333;
}

section
{
  line-height: 1.5em;
  padding: 20px;
  margin: 0 auto;
  width: 85%;
}
.handle{
  width: 100%;
  background: rgb(166, 43, 72);
  text-align: left;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  padding: 15px 20px;
  cursor: pointer;
  color: white;
  display: none;
}
@media all and (orientation: portrait){
  nav ul{
    max-height:0;
    float:right;
  }
  .showing{
    background-color:#333;
    max-height: 32em;
    max-width:20em;
    float:right;
  }
  nav ul li{
    width: 100%;
    text-align: right;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
       padding: 5%;
    font-size: 150%;
  }

  .handle{
    display: inline-block;
    text-align:right;
    float:right;
  }
  .icon {
  margin:0 auto;
  height:50px;
  width:70px;
  position:relative;
    float:right;
  }
  #hamburger-two {
  border-radius:100%;
}

#hamburger-two:before {
  content:'';
  display:block;
  position:absolute;
  height:80px;
  width:80px;
  background:transparent;
  top:-23px;
  left:-5px;
  border-radius:100%;
}

#hamburger-two:hover:before {

}

#hamburger-two span {
  display:block;
  width:70%;
  height:7px;
  left:15%;
  background:#fff;
  position:absolute;
}

#hamburger-two span:nth-of-type(1) {
  top:0px;
  left:auto;
  right:15%;
}

#hamburger-two span:nth-of-type(2) {
  top:14px;
}

#hamburger-two span:nth-of-type(2):before {
  content:'';
  display:block;
  position:absolute;
  top:0;
  left:0;
  background:#fff;
  width:100%;
  height:100%;
}

#hamburger-two span:nth-of-type(3) {
  top:28px;
  left:15%;
}

#hamburger-two.active:before {
  background:rgb(166, 43, 72);
}

#hamburger-two.active span:nth-of-type(1),#hamburger-two.active span:nth-of-type(3){
  width:0%;
}

#hamburger-two.active span:nth-of-type(2) {
  transform:rotate(45deg);
  background:#fff;
}

#hamburger-two.active span:nth-of-type(2):before {
  transform:rotate(90deg);
  background:#fff;
}
  *,*:before {
  transition:.25s ease-in-out;
}
}

@media screen and (max-width: 700px){
  nav ul{
    max-height:0;
    float:right;
  }
  .showing{
    background-color:#333;
    max-height: 32em;
    max-width:20em;
    float:right;
  }
  nav ul li{
    width: 100%;
    text-align: right;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
       padding: 5%;
    font-size: 150%;
  }

  .handle{
    display: inline-block;
    text-align:right;
    float:right;
  }
  .icon {
  margin:0 auto;
  height:50px;
  width:70px;
  position:relative;
    float:right;
  }
  #hamburger-two {
  border-radius:100%;
}

#hamburger-two:before {
  content:'';
  display:block;
  position:absolute;
  height:80px;
  width:80px;
  background:transparent;
  top:-23px;
  left:-5px;
  border-radius:100%;
}

#hamburger-two:hover:before {
  background:#fff;
}

#hamburger-two span {
  display:block;
  width:70%;
  height:7px;
  left:15%;
  background:#fff;
  position:absolute;
}

#hamburger-two span:nth-of-type(1) {
  top:0px;
  left:auto;
  right:15%;
}

#hamburger-two span:nth-of-type(2) {
  top:14px;
}

#hamburger-two span:nth-of-type(2):before {
  content:'';
  display:block;
  position:absolute;
  top:0;
  left:0;
  background:#fff;
  width:100%;
  height:100%;
}

#hamburger-two span:nth-of-type(3) {
  top:28px;
  left:15%;
}

#hamburger-two.active:before {
  background:rgb(166, 43, 72);
}

#hamburger-two.active span:nth-of-type(1),#hamburger-two.active span:nth-of-type(3){
  width:0%;
}

#hamburger-two.active span:nth-of-type(2) {
  transform:rotate(45deg);
  background:#fff;
}

#hamburger-two.active span:nth-of-type(2):before {
  transform:rotate(90deg);
  background:#fff;
}
  *,*:before {
  transition:.25s ease-in-out;
}
}


</style>
