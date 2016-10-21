<template>
            <div id="home1" class="info">
                <div id="titre-home">ENSEMBLE PRÉCIPITATIONS</div>
                <div id="texthome">LE BAROQUE, AUTREMENT.</div>
                <video id="imghome" controls src="src/assets/video/myVideo.mp4"></video>
                <div id="descriptionhome">Quand la musique baroque... <br>... rencontre les technologies de l'image.</div>
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

@font-face {
    font-family: "futura-book";
    src: url('../assets/Futura_Std/FuturaStd-Book.otf') ;
}

#home1{
    position: absolute;
    height: 100%;
    opacity: 1;
    width: 100%;
    z-index: 1;
}

#titre-home{
    text-align: center;
    position: absolute;
    top : 80px;
    left : 26%;
    font-size: 45px;
    font-family: "Gotham Medium";
}

#texthome{
    text-align: right;
    position: absolute;
    top : 150px;
    left : 31.5%;
    font-size: 25px;
    font-family: "futura-book";
}

#imghome{
    text-align: right;
    position: absolute;
    width: 480px;
    height: 300px;
    top : 230px;
    left : 22.5%;
    background-image: url('../assets/video/MyPoster.jpg');
    background-size: contain;
}

#descriptionhome {
    text-align: left;
    position: absolute;
    top : 550px;
    left : 22.5%;
    font-size: 25px;
    font-family: "futura-light";
}

@media all and (max-width : 1024px) {
  #titre-home{
      top : 60px;
      left : 28%;
      font-size: 35px;
  }
  #texthome{
      top : 130px;
      left : 31.5%;
      font-size: 22px;
  }

  #imghome{
      top : 200px;
      left : 20%;
  }

  #descriptionhome {
      top : 530px;
      left : 20%;
      font-size: 22px;
  }
}

@media all and (max-width : 768px) {
  #titre-home{
    top : 60px;
    left : 22%;
    font-size: 30px;
  }
  #texthome{
      top : 150px;
      left : 35%;
      font-size: 20px;
  }

  #imghome{
    width : 100%;
    max-width: 480px;
    top : 250px;
    left : 15%;
  }

  #descriptionhome {
      top : 600px;
      left : 80px;
      font-size: 20px;
  }
}

@media all and (max-width : 530px) {
  #imghome{
    width : 100%;
    max-width: 480px;
    top : 250px;
    left : 10px;
  }
}

@media all and (max-width : 480px) {

  #titre-home{
    top : 40px;
    left : 22%;
    font-size: 25px;
  }
  #texthome{
      top : 120px;
      left : 25%;
      font-size: 18px;
  }

  #imghome{
    width : 100%;
    height: 250px;
    top : 200px;
    left : 0px;
  }

  #descriptionhome {
    top : 460px;
    left : 20px;
    font-size: 20px;
  }
}

/* MOBILE */

@media all and (max-device-width : 1024px) {
  #titre-home{
      top : 60px;
      left : 28%;
      font-size: 35px;
  }
  #texthome{
      top : 130px;
      left : 31.5%;
      font-size: 22px;
  }

  #imghome{
      top : 200px;
      left : 20%;
  }

  #descriptionhome {
      top : 530px;
      left : 20%;
      font-size: 22px;
  }
}

@media all and (max-device-width: 768px) {
  #titre-home{
    top : 60px;
    left : 35%;
    font-size: 35px;
  }
  #texthome{
      top : 150px;
      left : 40%;
      font-size: 25px;
  }

  #imghome{
    width : 100%;
    max-width: 480px;
    top : 350px;
    left : 25%;
  }

  #descriptionhome {
    top : inherit;
    bottom : 10%;
    left : 25%;
    font-size: 20px;
  }
}

@media all and (max-device-width : 480px) {

  #titre-home{
    top : 11%;
    left : 50%;
    width: 25%;
    font-size: 300%;
  }

  #texthome{
    text-align: right;
    position: absolute;
    top : 35%;
    left : 38%;
    font-size: 250%;
    font-family: "futura-book";
  }

    #imghome{
        text-align: right;
        position: absolute;
        width: 75%;
        height: 30%;
        top : 40%;
        left : 13%;
    }

    #descriptionhome {
        text-align: left;
        position: absolute;
        top : 72%;
        left : 13%;
        font-size: 200%;
        font-family: "futura-light";
    }
}
</style>
