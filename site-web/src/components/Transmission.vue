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
    opacity: 1;
    height: 100%;
    width: 100%;
    z-index: 1;
}

#titre-transmission{
    text-align: right;
    position: absolute;
    top : 30px;
    left : 35%;
    font-family: "Gotham Medium";
    font-size: 50px;
}

#texttransmission{
    text-align: left;
    position: relative;
    top : 110px;
    left : 22%;
    width: 600px;
    font-size: 21px;
    font-family:"futura-light";
}

#img1transmission{
    text-align: right;
    position: absolute;
    background-image: url('../assets/img/img1-transmission.jpg');
    background-repeat: no-repeat;
    background-size: contain;
    height: 155px;
    width: 240px;
    top: 450px;
    left: 20%;
}

#img1transmissiontext{
    text-align: right;
    position: absolute;
    top: 410px;
    left: 20%;
    font-family: "futura-light";
    font-size: 19px;
}

#img2transmission{
    text-align: right;
    position: absolute;
    background-image: url('../assets/img/img2-transmission.jpg');
    background-repeat: no-repeat;
    background-size: contain;
    height: 155px;
    width: 240px;
    top: 250px;
    left: 20%;
}
#img2transmissiontext{
    text-align: right;
    position: absolute;
    top: 410px;
    left: 50%;
    font-family: "futura-light";
    font-size: 19px;
}

#img3transmission{
    text-align: right;
    position: absolute;
    background-image: url('../assets/img/img3-transmission.jpg');
    background-repeat: no-repeat;
    background-size: contain;
    height: 155px;
    width: 240px;
    top: 250px;
    left: 50%;
}
#img3transmissiontext{
    text-align: right;
    position: absolute;
    top: 610px;
    left: 20%;
    font-family: "futura-light";
    font-size: 19px;
}

@media all and (max-width : 1024px) {
  #titre-transmission{
    font-size: 45px;
    left: 30%;
  }
  #texttransmission{
    font-size: 20px;
    left: 20%;
    width: 450px;
  }

  #img2transmission{
    width: 220px;
    top: 280px;
    left: 15%;
  }
  #img1transmissiontext{
    font-size: 18px;
    left: 15%;
    top: 430px;
  }

  #img3transmission{
    height: 155px;
    width: 220px;
    top: 280px;
  }
  #img2transmissiontext{
    font-size: 18px;
    top: 430px;
  }

  #img1transmission{
    width: 220px;
    top: 480px;
    left: 15%;
  }
  #img3transmissiontext{
    top: 630px;
    left: 15%;
    font-size: 18px;
  }
}

@media all and (max-width : 768px) {
  #titre-transmission{
    font-size: 30px;
    left: 35%;
  }
  #texttransmission{
    font-size: 22px;
    left: 15%;
    width: 400px;
  }

  #img2transmission{
    width: 200px;
    top: 350px;
    left: 10%;
  }
  #img1transmissiontext{
    font-size: 18px;
    left: 10%;
    top: 490px;
  }

  #img3transmission{
    height: 155px;
    width: 200px;
    top: 350px;
    left: 55%;
  }
  #img2transmissiontext{
    font-size: 18px;
    top: 490px;
    left: 55%;
  }

  #img1transmission{
    width: 200px;
    top: 530px;
    left: 10%;
  }
  #img3transmissiontext{
    top: 670px;
    left: 10%;
    font-size: 18px;
  }
}

@media all and (max-width : 480px) {
  #titre-transmission{
    font-size: 25px;
    left: 30%;
  }
  #texttransmission{
    font-size: 20px;
    left: 5%;
    top: 80px;
    width: 320px;
  }

  #img2transmission{
    width: 150px;
    top: 310px;
    left: 20%;
  }
  #img1transmissiontext{
    font-size: 16px;
    left: 20%;
    top: 410px;
  }

  #img3transmission{
    height: 155px;
    width: 150px;
    top: 440px;
    left: 20%;
  }
  #img2transmissiontext{
    font-size: 16px;
    top: 540px;
    left: 20%;
  }

  #img1transmission{
    width: 150px;
    top: 570px;
    left: 20%;
  }
  #img3transmissiontext{
    top: 670px;
    left: 20%;
    font-size: 16px;
  }
}

@media all and (max-device-width : 1024px) {
  #titre-transmission{
    font-size: 65px;
    top: 80px;
    left: 30%;
  }
  #texttransmission{
    font-size: 35px;
    left: 20%;
    top: 200px;
    width: 600px;
  }

  #img2transmission{
    width: 300px;
    height: 300px;
    top: 600px;
    left: 120px;
  }
  #img1transmissiontext{
    font-size: 28px;
    left: 120px;
    top: 820px;
  }

  #img3transmission{
    height: 300px;
    width: 300px;
    top: 600px;
    left: 500px;
  }
  #img2transmissiontext{
    font-size: 28px;
    top: 820px;
    left: 500px;
  }

  #img1transmission{
    width: 300px;
    height: 300px;
    top: 900px;
    left: 120px;
  }
  #img3transmissiontext{
    top: 1110px;
    left: 120px;
    font-size: 28px;
  }
}

@media all and (max-device-width : 480px) {
  #titre-transmission{
    font-size: 60px;
    top: 60px;
    left: 30%;
  }
  #texttransmission{
    font-size: 40px;
    left: 150px;
    top: 200px;
    width: 650px;
  }

  #img2transmission{
    width: 380px;
    height: 300px;
    top: 700px;
    left: 100px;
  }
  #img1transmissiontext{
    font-size: 32px;
    left: 100px;
    top: 960px;
  }

  #img3transmission{
    height: 300px;
    width: 380px;
    top: 700px;
    left: 530px;
  }
  #img2transmissiontext{
    font-size: 32px;
    top: 960px;
    left: 530px;
  }

  #img1transmission{
    width: 380px;
    height: 300px;
    top: 1050px;
    left: 100px;
  }
  #img3transmissiontext{
    top: 1320px;
    left: 100px;
    font-size: 28px;
  }
}
</style>
