<template>
            <div id="home1" class="info">
                <div id="titre-home">ENSEMBLE PRÉCIPITATIONS</div>
                <div id="texthome">LE BAROQUE, AUTREMENT.</div>
                <video id="imghome" poster="video/myPoster.jpg" controls preload >
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
#home1{
        position: absolute;
        height: 100%;
        width: 100%;
        z-index: 1;
        opacity: 1;
    }

    #titre-home{
        text-align: left;
        position: absolute;
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
    }
  </style>
