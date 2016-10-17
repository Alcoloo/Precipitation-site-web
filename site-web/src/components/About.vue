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
#about1{
        position: absolute;
        opacity: 0;
        height: 100%;
        width: 100%;
        z-index: 1;
    }


    #textabout{
        text-align: right;
        position: absolute;
        font-size: 350%;
        top : 23%;
        left : 40%;
    }

    #text0about{
        margin: 0;
        margin-bottom:3%;
        color : #e08ba2;
    }

    #text1about{
    }

    #imgabout{
        text-align: right;
        position: absolute;
        background-size: contain;
        background-repeat: no-repeat;
        height: 30%;
        width: 75%;
        top : 35%;
        left : 15%;
    }

    #descriptionabout {
        text-align: left;
        font-size:220%;
        position: absolute;
        width: 74%;
        top : 57%;
        left : 15%;
    }
</style>
