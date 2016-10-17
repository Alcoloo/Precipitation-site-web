<template>
  <div id="transmission1" class="info">
                <div id="titre-transmission">TRANSMISSION</div>
                <div id="texttransmission">L’ensemble Précipitations a la transmission, au cœur de ses valeurs.
                Ateliers, conférences, initiations... Notre directeur musical et nos musiciens peuvent intervenir de diverses manières pour transmettre leur savoir, leurs projets, ainsi que des thèmes plus larges comme le baroque...
                </div>
                <div id="img1transmission"></div>
                <div id="img1transmissiontext">Ateliers instruments anciens…</div>
                <div id="img2transmission"></div>
                <div id="img2transmissiontext">Ateliers musiciens…</div>
                <div id="img3transmission"></div>
                <div id="img3transmissiontext">Conférences…</div>
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

<style scoped>

@font-face {
    font-family: "futura-light";
    src: url('../assets/Futura_Std/FuturaStd-Light.otf') ;
}

@font-face {
    font-family: "Gotham Medium";
    src: url('../assets/Futura_Std/gotham-medium.ttf') ;
}

#transmission1{
    position: absolute;
    -webkit-transform:translateZ(-148px);
    -moz-transform:translateZ(-148px);
    opacity: 1;
    height: 100%;
    width: 100%;
    z-index: 1;
}

#titre-transmission{
    text-align: right;
    position: absolute;
    top : 7%;
    left : 30%;
    font-family: "Gotham Medium";
    font-size: 350%;
}

#texttransmission{
    text-align: left;
    position: relative;
    top : 15%;
    left : 22%;
    width: 37%;
    font-size: 135%;
    font-family:"futura-light";
}

#img1transmission{
    text-align: right;
    position: absolute;
    background-image: url('../assets/img/img1-transmission.jpg');
    background-repeat: no-repeat;
    background-size: contain;
    height: 23%;
    width: 23%;
    top : 60%;
    left : 20%;
}

#img1transmissiontext{
    text-align: right;
    position: absolute;
    top : 55%;
    left : 20%;
    font-family:"futura-light";
    font-size: 150%;
}

#img2transmission{
    text-align: right;
    position: absolute;
    background-image: url('../assets/img/img2-transmission.jpg');
    background-repeat: no-repeat;
    background-size: contain;
    height: 23%;
    width: 23%;
    top : 30%;
    left : 20%;
}
#img2transmissiontext{
    text-align: right;
    position: absolute;
    top : 55%;
    left : 40%;
    font-family:"futura-light";
    font-size: 150%;
}

#img3transmission{
    text-align: right;
    position: absolute;
    background-image: url('../assets/img/img3-transmission.jpg');
    background-repeat: no-repeat;
    background-size: contain;
    height: 23%;
    width: 23%;
    top : 30%;
    left : 40%;
}
#img3transmissiontext{
    text-align: right;
    position: absolute;
    top : 85%;
    left : 20%;
    font-family:"futura-light";
    font-size: 150%;
}
</style>
