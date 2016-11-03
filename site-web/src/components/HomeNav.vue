<template>
            <div id="home1" class="info">
                <div id="titre-home">ENSEMBLE PRÉCIPITATIONS</div>
                <div id="texthome">LE BAROQUE, AUTREMENT.</div>
                <video id="imghome" controls ><source src="src/assets/video/myVideo.mp4" type="video/mp4"></video>
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
    font-weight: bold;
    letter-spacing: 2px;
    top : 90px;
    left : 24.5%;
    font-size: 30px;
    font-family: "Gotham Medium";
}

#texthome{
    text-align: right;
    position: absolute;
    top : 235px;
    left : 27.5%;
    font-size: 20px;
    font-family: "futura-book";
}

#imghome{
    text-align: right;
    position: absolute;
    width: 600px;
    height: 350px;
    top : 350px;
    left : 17.5%;
    /*background-image: url('../assets/video/MyPoster.jpg');
    background-size: contain;*/
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
      top : 100px;
      left : 28%;
      font-size: 35px;
  }
  #texthome{
      top : 200px;
      left : 31.5%;
      font-size: 22px;
  }

  #imghome{
      top : 300px;
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

/* --------------------  MOBILE  -------------------- */

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
    text-align: left;
    top : 60px;
    left : 45%;
    font-size: 55px;
  }
  #texthome{
      top : 250px;
      left : 40%;
      font-size: 40px;
  }

  #imghome{
    width : 760px;
    height: 427.5px;
    top : 450px;
    left :10%;
  }

  #descriptionhome {
    top : inherit;
    bottom : 15%;
    left : 10%;
    font-size: 40px;
  }
}

@media all and (max-device-width : 480px) {

  #titre-home{
    top : 150px;
    left : 45%;
    width: 25%;
    font-size: 55px;
  }

  #texthome{
    top : 350px;
    left : 30%;
    font-size: 40px;
  }

  #imghome{
      width:800px;
      max-width: none;
      height: 450px;
      top : 600px;
      left : 10%;
  }

  #descriptionhome {
      top : inherit;
      bottom: 150px;
      left : 13%;
      font-size: 40px;
      font-family: "futura-light";
  }
}
</style>
