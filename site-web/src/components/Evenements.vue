<template>
  <div id="event1" class="info">
    <div id="textevent"> ÉVÈNEMENTS </div>
    <div id="imgevent">
      <div id = "event1left">
        <h1 id = "event1H">TEARS OF THE NYMPH [1]</h1><br>
            <p id='event1Pcolor' style = "color : rgb(166, 43, 72)">PERFORMANCE ÉVOLUTIVE</p><br>
            <p id="event1P">Piersten Leirom, performeur<br>
                          Grégoire Lorieux, électronique<br>
                          Précipitations & Sébastien Amadieu<br><br>
                          Eglise des Billettes, Paris
            </p>
      </div>
        <div id ='event1deco'></div>
        <div id="event1right">
          <div id='eventDate'>
            <div id='event1imgCalendar'></div>16 OCT. 2016<br>
            <a id='event1plus'>en voir plus >></a>
          </div>
          <div id="event1img"></div>
        </div>
    </div>

    <div id="img1event">
      <div id = "event2right">
          <h1 id = "event2H">IN NOMINE...</h1><br>
            <p id='event2Pcolor' style = "color : rgb(166, 43, 72)">RÉCITAL - DUO CLAVECIN & VIOLON</p><br>
            <p id="event2P">Nathalie Fontaine, violon<br>
                            Sébastien Amadieu, clavecin<br><br>
                            Temple de Levallois-Perret
            </p>
        </div>
        <div id ='event2deco'></div>
        <div id="event2left">
          <div id='event2Date'>
            <div id='event2imgCalendar'></div>7 AVRIL 2016<br>
            <a id='event2plus'>en voir plus >></a>
          </div>
          <div id="event2img"></div>
        </div>
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

#event1{
    position: absolute;
    height: 100%;
    width: 100%;
    z-index: 1;
}

#textevent{
    font-family: "Gotham Medium";
    text-align: right;
    position: absolute;
    font-size: 45px;
    top : 80px;
    left : 45%;
}
    /* EVENT 1 */

#imgevent{
  position: relative;
  top : 180px;
  left : 30%;
  width:400px;
  height: 24%;
}
#event1left{
  position: absolute;
  height: 27%;
  width: 60%;
  top : -15%;
  left : 0%;
}

#event1right{
  position: absolute;
  height: 100%;
  width: 80%;
  top : 8px;
  left : 100%;
}

#event1imgCalendar{
  background-image: url('../assets/img/calendrier_event.png');
  background-size: contain;
  background-repeat: no-repeat;
  width: 50px;
  height: 100%;
  top: 0%;
  left:-30px;
  position: absolute;
}

#eventDate{
  font-family: "futura-book";
  position: absolute;
  top:0%;
  left:15%;
  font-size: 20px;
}

#event1plus{
  font-family: "futura-light-oblique";
  position: absolute;
  top: 140%;
  left:-30px;
  font-size: 18px;
  width: 200%;
}

#event1img{
  position : absolute;
  background:url('../assets/img/img1-event.jpg');
  background-size: contain;
  background-repeat: no-repeat;
  left: 20px;
  top: 30%;
  width: 190px;
  height:150px;
}

#event1deco{
  position: relative;
  width: 10px;
  height: 100%;
  top : 0%;
  left : 100%;
  background-color: rgb(166, 43, 72);
}

#event1H{
  position : absolute;
  top : 10px;
  left: 0;
  width: 200%;
  height: 5%;
  text-align: left;
  font-family: "futura-heavy";
  font-size: 33px;
}
#event1Pcolor{
  font-family: "futura-book";
  position : relative;
  text-align: right;
  top : 40px;
  right : 95px;
  width: 200%;
  font-size: 23px;
}

#event1P{
  font-family: "futura-book";
  text-align: right;
  position : relative;
  bottom : 30px;
  right : 95px;
  width: 200%;
  font-size: 23px;
}

/* EVENT 2 */

#img1event{
    position: relative;
    height: 22%;
    width: 44%;
    top : 230px;
    left : 10%;
}

#event2left{
  position: absolute;
  height: 100%;
  width: 160px;
  top : -20px;
  left : 20px;
}

#event2right{
  position: absolute;
  height: 47%;
  width: 65%;
  top : -20px;
  left : 210px;
}

#event2imgCalendar{
  background-image: url('../assets/img/calendrier_event.png');
  background-size: contain;
  background-repeat: no-repeat;
  width: 50px;
  height: 30px;
  top: -3px;
  left: -40px;
  position: absolute;
}

#event2Date{
  font-family: "futura-book";
  position: absolute;
  text-align: right;
  top: 30px;
  left: 35px;
  font-size: 20px;
}

#event2plus{
  font-family: "futura-light-oblique";
  position: relative;
  top: 30px;
  left: 0px;
  width: 120%;
  font-size: 18px;
}

#event2img{
  position : absolute;
  background:url('../assets/img/img2-event.jpg');
  background-size: contain;
  background-repeat: no-repeat;
  left: -30px;
  top: 125px;
  width: 190px;
  height: 110px;
}

#event2deco{
  position: relative;
  width: 10px;
  height: 107%;
  top: 0;
  left: 190px;
  background-color: rgb(166, 43, 72);
}

#event2H{
  position : absolute;
  top : 0;
  left: 0%;
  width: 200px;
  height: 5%;
  text-align: left;
  font-family: "futura-heavy";
  font-size: 33px;
}
#event2Pcolor{
  font-family: "futura-book";
  position : absolute;
  text-align: left;
  width: 390px;
  top : 50px;
  left : 0;
  font-size: 23px;
}

#event2P{
  font-family: "futura-book";
  text-align: left;
  position : absolute;
  top : 95px;
  left: 0%;
  width: 290px;
  height: 10%;
  font-size: 23px;
}

@media all and (max-width : 1024px) {
  #textevent{
    font-size: 35px;
    left : 50%;
    top : 50px;
  }
  /* EVENT 1 */
  #imgevent{
    top : 130px;
    left :10%;
  }
  #event1left #event1H{
    font-size: 28px;
    top : 15px;
    left : 75px;
  }
  #event1left #event1Pcolor{
    font-size: 20px;
  }
  #event1left #event1P{
    font-size: 20px;
    top : 0px;
  }
  #event1right #eventDate{
    font-size: 18px;
  }
  #event1right #eventDate #event1plus{
    font-size: 16px;
  }

  /* EVENT 2 */
  #img1event{
    top : 180px;
    left : 10%;
  }
  #event2right #event2H{
    font-size: 28px;
    top : 15px;
    left : 0px;
  }
  #event2right #event2Pcolor{
    font-size: 20px;
  }
  #event2right #event2P{
    font-size: 20px;
    top : 110px;
  }
  #event2left #event2Date{
    font-size: 18px;
    left : 45px;
    top : 40px;
  }
  #event2left #eventDate #event2plus{
    font-size: 16px;
  }
  #event2deco{
    height: 100%;
    top : 14px;
  }
}
@media all and (max-width : 768px) {
  #textevent{
    font-size: 30px;
    left : 45%;
    top : 50px;
  }
  /* EVENT 1 */
  #imgevent{
    top: 130px;
    left: inherit;
    right: 170px;
    position: absolute;
  }
  #event1left{
    width: 45%;
  }
  #event1deco{
    left: 280px;
    height: 177px;
  }
  #event1left #event1H{
    font-size: 22px;
    top: 17px;
    left: 10px;
  }
  #event1left #event1Pcolor{
    font-size: 17px;
    top: 40px;
  }
  #event1left #event1P{
    font-size: 16px;
    top: 0px;
  }

  #event1right{
    top: -10px;
    left: 280px;
  }
  #event1right #eventDate{
    font-size: 15px;
    top: 10px;
  }
  #event1right #eventDate #event1plus{
    font-size: 14px;
    top: 35px;
  }
  #event1right #event1img{
    left: 20px;
    top: 66px;
    width: 160px;
    height: 150px;
  }

  /* EVENT 2 */
  #img1event{
    top: 390px;
    left: 0px;
    position: absolute;
  }
  #event2right #event2H{
    font-size: 22px;
    top: 17px;
    left: 0px;
  }
  #event2right #event2Pcolor{
    font-size: 16px;
  }
  #event2right #event2P{
    font-size: 16px;
    top: 90px;
  }
  #event2left{
    top: -20px;
    left: 30px;
  }
  #event2left #event2Date{
    font-size: 16px;
    left: 45px;
    top: 40px;
  }
  #event2left #event2Date #event2imgCalendar{
    width: 30px;
    height: 30px;
    top: -5px;
    left: -35px;
  }
  #event2left #event2Date #event2plus{
    top: 10px;
    left: 0px;
    width: 120%;
    font-size: 14px;
  }
  #event2left #event2img{
    left: 0px;
    top: 103px;
    width: 150px;
    height: 90px;
  }
  #event2deco{
    height: 153px;
    top: 14px;
    left: 190px;
  }
}
@media all and (max-width : 580px) {
  #imgevent{
    right: inherit;
    left: 0;
  }
}

@media all and (max-device-width : 1024px) {
  #textevent{
    font-size: 60px;
    left: 35%;
    top: 90px;
  }
  /* EVENT 1 */
  #imgevent{
    top: 280px;
    left: 150px;
  }
  #event1left #event1H{
    font-size: 40px;
    top: 15px;
    left: -60px;
  }
  #event1left #event1Pcolor{
    font-size: 30px;
  }
  #event1left #event1P{
    font-size: 30px;
    top: 0px;
  }
  #event1left #event1deco{
    left: 400px;
  }
  #event1right #eventDate{
    font-size: 32px;
    left: 60px;
  }
  #event1right #eventDate #event1imgCalendar{
    width: 50px;
    height: 100%;
    top: 0%;
    left: -40px;
  }
  #event1right #eventDate #event1plus{
    font-size: 25px;
  }
  #event1right #event1img{
    left: 20px;
    top: 30%;
    width: 280px;
    height: 230px;
  }

  /* EVENT 2 */
  #img1event{
    top: 500px;
    left: 150px;
  }
  #event2right #event2H{
    font-size: 40px;
    top: 5px;
    left: 0px;
    width: 250px;
  }
  #event2right #event2Pcolor{
    font-size: 30px;
    width: 500px;
  }
  #event2right #event2P{
    font-size: 30px;
    top: 110px;
    width: 500px;
  }
  #event2left{
    width: 160px;
    top: -20px;
    left: 20px;
  }
  #event2left #event2Date{
    font-size: 32px;
    left: -35px;
    top: 40px;
  }
  #event2left #event2Date #event2imgCalendar{
    width: 50px;
    height: 50px;
    top: -3px;
    left: -60px;
  }
  #event2left #event2Date #event2plus{
    top: 20px;
    left: 0px;
    width: 120%;
    font-size: 25px;
  }
  #event2left #event2img{
    left: -90px;
    top: 145px;
    width: 250px;
    height: 200px;
  }
  #event2deco{
    height: 252px;
    top: 14px;
  }
}

@media all and (max-device-width : 480px) {
  #textevent{
    font-size: 80px;
    left: 30%;
    top: 130px;
  }
  /* EVENT 1 */
  #imgevent{
    top: 400px;
    left: 180px;
  }
  #event1left #event1H{
    font-size: 45px;
    top: 21px;
    left: -120px;
    width: 520px;
  }
  #event1left #event1Pcolor{
    font-size: 35px;
    top: 70px;
  }
  #event1left #event1P{
    font-size: 35px;
    width: 550px;
    left: -170px;
  }
  #event1left #event1deco{
    left: 400px;
  }
  #event1right #eventDate{
    font-size: 32px;
    left: 65px;
  }
  #event1right #eventDate #event1imgCalendar{
    left: -45px;
  }
  #event1right #eventDate #event1plus{
    font-size: 30px;
    left: -40px;
  }
  #event1right #event1img{
    width: 315px;
    height: 310px;
  }

  /* EVENT 2 */
  #img1event{
    top: 540px;
    left: 150px;
  }
  #event2right #event2H{
    font-size: 45px;
    width: 280px;
  }
  #event2right #event2Pcolor{
    font-size: 35px;
    width: 600px;
    top: 70px;
  }
  #event2right #event2P{
    font-size: 35px;
    top: 133px;
    width: 500px;
  }
  #event2left{
    width: 160px;
    top: -20px;
    left: 20px;
  }
  #event2left #event2Date #event2imgCalendar{
    width: 50px;
    height: 50px;
    top: -3px;
    left: -60px;
  }
  #event2left #event2Date #event2plus{
    top: 30px;
  }
  #event2left #event2img{
    left: -150px;
    top: 165px;
    width: 310px;
  }
  #event2deco{
    height: 306px;
  }
}
</style>
