<template>
  <div id= "header">
    <nav>
      <ul>
        <li id ="lihome" class="active"><button id="homeButton">Accueil</button></li>
        <li id ="liabout"><button id="aboutButton">A Propos</button></li>
        <li id ="lievent"><button id="eventButton">Evènement</button></li>
        <li id ="litransmission"><button id="transmissionButton">Transmission</button></li>
        <li id ="limecenat"><button id="mecenatButton">Mécenat</button></li>
        <li id ="licontact"><button id="contactButton">Contact</button></li>
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

    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
* {
margin: 0;
padding: 0;
}
#header{
  background-color:rgb(166, 43, 72);
  position :absolute;
  width: 100%;
  top:0px;
  left: 0px;
  z-index: 99;
}
button{
  border: none;
  background: none;
  outline: none;
  font-size: larger;
}


nav {
  margin:auto;
  padding: 20px;
  position: relative;
  display: flex;
 justify-content: center;
 max-width: 1080px;
 margin: auto;
}

/* list styles */
ul {
margin: 0px auto;
overflow: auto;
list-style: none;
}

li {
font-family: Open Sans, sans-serif;
font-size: 20px;
font-weight:300;
float: left;
padding-right: 20px;
padding-left: 20px;
border-right: 1px solid #999;
}

li:last-child {
border: none;
}

li button {
text-decoration: none;
color: #888;

/* transitions & animations
transition: all .5s ease;
-webkit-transition: all .5s ease;
-moz-transition: all .5s ease;
-o-transition: all .5s ease; */
}

li button:hover {
color: #333;
}

li.active button {
color: #F15A24;
font-weight: normal;
}
</style>
