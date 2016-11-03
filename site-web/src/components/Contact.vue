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

#contact1
{
  position: absolute;
  opacity: 1;
  height: 100%;
  width: 100%;
  z-index: 1;
}

#textcontact
{
  font-family: "Gotham Medium";
  text-align: right;
  position: fixed;
  font-size: 40px;
  top : 150px;
  left : 34%;
}

#text1contact
{
  font-family: "futura-book";
  text-align: left;
  position: fixed;;
  width : 530px;
  font-weight: bold;
  font-size: 16px;
  top : 300px;
  left : 17.5%;
}

/*-------------- FORMULAIRE --------------*/

#formulaire
{
    position : relative;
    height: auto;
}

.form-horizontal
{
    position: fixed;
    left : 16.5%;
    font-size: 17px;
    color : white;
}

.col-md-4{
    background-color: rgb(166, 43, 72);
}

.form-control
{
    background-color: rgb(166, 43, 72);
    font-size: 17px;
    color : white;
    width:500px;
}

*
{
    border :0px;
}

.name
{
    font-family: "futura-light";
    background-color: rgb(166, 43, 72);
    position: fixed;
    width : 575px;
    top : 450px;
    height: inherit;
    padding: 0.3%;
}

.email
{
    font-family: "futura-light";
    background-color: rgb(166, 43, 72);
    position: fixed;
    width : 575px;
    top : 510px;
    height: inherit;
    padding: 0.3%;
}
.sujet
{
    font-family: "futura-light";
    background-color: rgb(166, 43, 72);
    position: fixed;
    width : 575px;
    top : 570px;
    height: inherit;
    padding: 0.3%;
}

.message
{
    font-family: "futura-light";
    position: fixed;
    background-color: rgb(166, 43, 72);
    width : 575px;
    height: 100px;
    top : 630px;
    padding: 0.3%;
}


#messageForm
{
  width : 570px;
  font-size: 17px;
  color : white;
  resize: none;
}

.bouton .col-md-4{
    position: fixed;
    text-align: center;
    font-family: "futura-light";
    width: 100px;
    top : 750px;
    left : 30%;
    font-size: 13px;
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
    font-size: 14px;
    top : 800px;
    left : 17.5%;
}
</style>
