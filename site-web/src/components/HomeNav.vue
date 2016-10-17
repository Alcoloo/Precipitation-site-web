<template>
            <div id="home1" class="info">
                <div id="titre-home">ENSEMBLE PRÉCIPITATIONS</div>
                <div id="texthome">LE BAROQUE, AUTREMENT.</div>
                <video id="imghome" poster=".src\assets\video\myPoster.jpg" controls preload >
				<source src="video/myVideo.mp4" type="video/mp4" />
      </video>
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
    opacity: 0;
    width: 100%;
    z-index: 1;
}

#titre-home{
    text-align: center;
    position: absolute;
    top : 10%;
    left : 25%;
    font-size: 250%;
    font-family: "Gotham Medium";
}

#texthome{
    text-align: right;
    position: absolute;
    top : 25%;
    left : 28.2%;
    font-size: 150%;
    font-family: "futura-book";
}

#imghome{
    text-align: right;
    position: absolute;
    width: 30%;
    height: 40%;
    top : 32%;
    left : 17%;
}

#descriptionhome {
    text-align: left;
    position: absolute;
    top : 75%;
    left : 17%;
    font-size: 150%;
    font-family: "futura-light";
}
</style>
