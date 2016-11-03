<template>
  <div id="mecenat1" class="info">
                <div id="textmecenat">MÉCÉNAT</div>
                <div id="defMecenat">Le mécénat désigne le fait d'aider et peut être par la suite de promouvoir des arts et des lettres par des commandes ou des aides financières privées, que le mécène soit une personne physique ou une personne morale, comme une entreprise.
                </div>
                <div id="descriptionmecenat">Entreprise ou particulier, nul n’est besoin d’investir de grands montants pour être mécène : en rejoignant l’un des cercles de mécènes de Précipitations, vous devenez un acteur de la vie culturelle française et participez au rayonnement de l’ensemble et de ses propositions artistiques dans le monde entier. Votre soutien se traduit immédiatement par de nouvelles réalisations, et le lien que vous tisserez avec les artistes de l’ensemble continuera à grandir avec le temps.</div>
                <div id='avantageMecenat'><h1 id='titreAvantage'>LES AVANTAGES</h1><br>
                    <a style="color : rgb(166, 43, 72)">+</a> Invitation aux diverses prestations de l’ensemble<br>
                    <a style="color : rgb(166, 43, 72)">+</a>  Devenir acteur de la vie artistique en France<br>
                    <a style="color : rgb(166, 43, 72)">+</a>  Déduction fiscale grâce à votre don...<br><br>
                    <a id='mecenatplus'>Télécharger la plaquette sur le mécenat >></a>
                    <div id='decoAvantages'></div>
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
    font-family: "futura-book";
    src: url('../assets/Futura_Std/FuturaStd-Book.otf') ;
}

@font-face {
    font-family: "futura-light-oblique";
    src: url('../assets/Futura_Std/FuturaStd-LightOblique.otf') ;
}

@font-face {
    font-family: "futura-heavy";
    src: url('../assets/Futura_Std/FuturaStd-Heavy.otf') ;
}

@font-face {
    font-family: "futura-light";
    src: url('../assets/Futura_Std/FuturaStd-Light.otf') ;
}

#mecenat1{
    position: absolute;
    height: 100%;
    width: 100%;
    z-index: 1;
}

#textmecenat{
    font-family: "Gotham Medium";
    text-align: right;
    font-size: 400%;
    position: absolute;
    top : 10%;
    left : 35%;
}


#defMecenat{
    text-align: left;
    font-family: "futura-light";
    font-size: 135%;
    position: absolute;
    height: 10%;
    width: 35%;
    top : 21%;
    left : 21%;
}

#descriptionmecenat {
    font-family: "futura-book";
    text-align: left;
    position: absolute;
    top : 37%;
    left : 10%;
    width: 50%;
    height: 20%;
    font-size:145%;
}

#titreAvantage{
    font-family: "futura-heavy";
    font-size: 225%;
    text-align: left;
}

#avantageMecenat {
    font-family: "futura-book";
    text-align: left;
    position: absolute;
    top : 60%;
    left : 12.1%;
    width: 45%;
    height: 20%;
    font-size: 135%;
}

#decoAvantages{
    position: absolute;
    width: 1.5%;
    height: 115%;
    top : 2%;
    left : -5%;
    background-color: rgb(166, 43, 72);
}

#mecenatplus{
    font-family: 'futura-light-oblique';
}

</style>
