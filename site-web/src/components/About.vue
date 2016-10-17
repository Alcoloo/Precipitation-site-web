<template>
<div id="about1" class="info">
                <div id="textabout"><div id="text0about">ensemble</div>
                                    <div id="text1about">PRÉCIPITATIONS</div>
                </div>
                <div id="imgabout"></div>
                <div id="descriptionabout">Précipitations est un ensemble musical baroque qui propose une ré-interprétation des œuvres du XVIe au XVIIIe siècle lors de spectacles et performances. Cet ensemble ajoute à cet orchestre d’autres arts (vivants) et technologies (de l’image), pour enrichir ses performances (ex : théâtre, danse, vidéo, poésie, etc.).<br> Association basée à Levallois-Perret et dirigée par Sébastien AMADIEU.
</div>
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
    font-family: "Gotham Medium";
    src: url('../assets/Futura_Std/gotham-medium.ttf') ;
}

@font-face {
    font-family: "futura-light";
    src: url('../assets/Futura_Std/FuturaStd-Light.otf') ;
}

#about1{
    position: absolute;
    -webkit-transform:translateZ(-48px);
    -moz-transform:translateZ(-48px);
    opacity: 0;
    height: 100%;
    width: 100%;
    z-index: 1;
}


#textabout{
    text-align: right;
    position: absolute;
    font-size: 350%;
    top : 12%;
    left : 30%;
}

#text0about{
    font-family: 'Gotham Medium';
    margin: 0;
    margin-bottom:3%;
    color : #e08ba2;
}

#text1about{
    font-family: 'Gotham Medium';
}

#imgabout{
    text-align: right;
    position: absolute;
    background-image: url('../assets/img/img-apropos.jpg');
    background-size: contain;
    background-repeat: no-repeat;
    height: 33%;
    width: 41%;
    top : 28%;
    left : 16.4%;
}

#descriptionabout {
    text-align: left;
    font-family: 'futura-light';
    font-size:125%;
    position: absolute;
    width: 42%;
    top : 65%;
    left : 16.4%;
}

</style>
