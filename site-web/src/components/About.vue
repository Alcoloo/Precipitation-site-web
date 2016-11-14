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
    opacity: 1;
    height: 100%;
    width: 100%;
    z-index: 1;
}


#textabout{
    text-align: right;
    position: absolute;
    font-weight: bold;
    font-size: 40px;
    top : 110px;
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
    width: 800px;
    top : 265px;
    left : 15.75%;
    height: 100%;
}

#descriptionabout {
    text-align: left;
    font-family: 'futura-light';
    position: absolute;
    font-size:16px;
    width: 800px;
    top : 630px;
    left : 15.75%;
}

@media all and (max-width : 1024px){

  #textabout
  {
    font-size: 38px;
    top : 100px;
    left : 40%;
  }

  #imgabout
  {
    width : 540px;
    top : 250px;
    left : 25.5%;
  }

  #descriptionabout
  {
    font-size:20px;
    width: 540px;
    top : 500px;
    left : 25.5%;
  }

}

@media all and (max-width : 960px){

  #textabout
  {
    font-size: 38px;
    top : 100px;
    left : 37%;
  }

  #imgabout
  {
    width : 540px;
    top : 250px;
    left : 22.5%;
  }

  #descriptionabout
  {
    font-size:20px;
    width: 540px;
    top : 500px;
    left : 22.5%;
  }

}

@media all and (max-width : 768px){

  #textabout
  {
    font-size: 30px;
    top : 150px;
    left : 35%;
  }

  #imgabout
  {
    width: 350px;
    top : 300px;
    left : 25%;
  }

  #descriptionabout
  {
    font-size:15px;
    width: 350px;
    top : 500px;
    left : 25%;
  }

}

@media all and (max-width : 650px){

  #textabout
  {
    font-size: 30px;
    top : 150px;
    left : 35%;
  }

  #imgabout
  {
    width: 350px;
    top : 300px;
    left : 25.5%;
  }

  #descriptionabout
  {
    font-size:15px;
    width: 350px;
    top : 500px;
    left : 25.5%;
  }

}

@media all and (max-width:480px) {

  #textabout
  {
    font-size: 350%;
    top : 130px;
    left : 34%;
  }

  #imgabout
  {
    height: 33%;
    width: 41%;
    top : 360px;
    left : 16.4%;
  }

  #descriptionabout
  {
    font-size:125%;
    position: absolute;
    width: 42%;
    top : 800px;
    left : 16.4%;
  }


}


</style>
