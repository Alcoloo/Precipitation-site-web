<template>
  <div id="contact1" class="info">
                <div id="textcontact">CONTACT</div>
                <div id="text1contact">Précipitations répond à vos questions.<br>
Merci de remplir ce formulaire avec vos coordonnées et de nous adresser votre message (informations, prestations, etc.).</div>
                <div id="formulaire">
                    <form class="form-horizontal">
                        <fieldset>
                        <!-- Text input-->
                        <div class="form-group name " >
                          <label class="col-md-4 control-label FuturaBook" style="float:left" for="name">NOM /</label>
                          <div class="col-md-4" style="float:left">
                          <input id="name" name="name" type="text" class="form-control input-md FuturaLight">

                          </div>
                        </div>

                        <!-- Text input-->
                        <div class="form-group email" style="clear : left ; float:left">
                          <label class="col-md-4 control-label FuturaBook"  style="float:left" for="email">EMAIL /</label>
                          <div class="col-md-4" style="float:left">
                          <input id="email" name="email" type="text" placeholder="" class="form-control input-md FuturaLight">
                          </div>
                        </div>

                        <!-- Text input-->
                        <div class="form-group sujet"  style="clear : left ; float:left">
                          <label class="col-md-4 control-label FuturaBook" style="float:left" for="sujet">SUJET /</label>
                          <div class="col-md-4" style="float:left">
                          <input id="sujet" name="sujet" type="text" placeholder="" class="form-control input-md FuturaLight">

                          </div>
                        </div>

                        <!-- Textarea -->
                        <div class="form-group message" style="float : none">
                          <label class="col-md-4 control-label FuturaBook" for="message">MESSAGE /</label>
                          <div id="divMessageForm" class="col-md-4">
                            <textarea class="form-control FuturaLight"  id="messageForm" name="message"></textarea>
                          </div>
                        </div>

                        <!-- Button -->
                        <div class="form-group bouton" style="clear : both">
                          <label class="col-md-4 control-label" for="submit"></label>
                          <div class="col-md-4">
                            <button id="submit" name="submit" class="btn btn-default FuturaBook">ENVOYER</button>
                          </div>
                        </div>

                        </fieldset>
                    </form>
                </div>
                <div id="descriptioncontact">Association Précipitations (statut de loi 1901)<br>
                                            76, rue Marius Aufan 92300 Levallois-Perret<br>
                                            06 63 20 01 69  |  09 73 17 89 13</div>
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

#contact1{
    position: absolute;
    height: 100%;
    width: 100%;
    z-index: 1;
}

#textcontact{
    font-family: "Gotham Medium";
   text-align: right;
    position: fixed;
    font-size: 350%;
    top : 10%;
    left : 34%;
}
#text1contact{
    font-family: "futura-book";
   text-align: left;
    position: fixed;
    width: 28%;
    font-size: 150%;
    top : 25%;
    left : 19%;
}

/*-------------- FORMULAIRE --------------*/

#formulaire{
    position : relative;
    width:50%;
    height: auto;
}
.form-horizontal{
    position: fixed;
    width: 50%;
    height: auto;
    top : 45%;
    left : 18%;
    font-size: 150%;
    color : white;
}
.col-md-4{
    background-color: rgb(166, 43, 72);
}
.form-control{
    background-color: rgb(166, 43, 72);
    font-size: 100%;
    color : white;
    width:220%;
}

*{
    border :0px;
}
.name{
    font-family: "futura-light";
    background-color: rgb(166, 43, 72);
    position: fixed;
    width : 30%;
    top : 40%;
    height: inherit;
    padding: 0.3%;
}
.email{
    font-family: "futura-light";
    background-color: rgb(166, 43, 72);
    position: fixed;
    width : 30%;
    top : 46%;
    height: inherit;
    padding: 0.3%;
}
.sujet{
    font-family: "futura-light";
    background-color: rgb(166, 43, 72);
    position: fixed;
    width : 30%;
    top : 52%;
    height: inherit;
    padding: 0.3%;
}

.message{
    font-family: "futura-light";
    position: fixed;
    background-color: rgb(166, 43, 72);
    width : 30%;
    height: 10%;
    top : 58%;
    padding: 0.3%;
}
#divMessageForm{
    font-family: "futura-light";
    height:70%;
    width: 100%;
}
#messageForm{
    height:80%;
    width: 80%;
    font-size: 150%;
    color : white;
    resize: none;

}

.bouton .col-md-4{
    position: fixed;
    text-align: center;
    font-family: "futura-light";
    font-size: larger;
    width : 5%;
    top : 70%;
    left : 30%;
    font-size: 50%;
    height: inherit;
    padding: 0.3%;
    background-color: #e08ba2;
}

button
{
  background: none;
}


/*--------------FIN FORMULAIRE --------------*/



#descriptioncontact {
    font-family: "futura-light";
    text-align: left;
    position: fixed;
    font-size: 90%;
    top : 77%;
    left : 19%;
}
</style>
