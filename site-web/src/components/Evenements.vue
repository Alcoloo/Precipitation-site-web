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
                          <div id='eventDate'><div id='event1imgCalendar'></div>16 OCT. 2016<br>
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
                          <div id='event2Date'><div id='event2imgCalendar'></div>7 AVRIL 2016<br>
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
        -webkit-transform:translateZ(-98px);
        -moz--transform:translateZ(-98px);
        opacity: 0;
        height: 100%;
        width: 100%;
        z-index: 1;
    }

    #textevent{
        font-family: "Gotham Medium";
        text-align: right;
        position: absolute;
        font-size: 300%;
        top : 15%;
        left : 50%;
    }
    /* EVENT 1 */

    #imgevent{
        position: relative;
        top : 38%;
        left : 15%;
        width:41%;
        height: 24%;

    }
            #event1left{
                position: absolute;
                height: 27%;
                width: 60%;
                top : 0%;
                left : 0%;
            }

            #event1right{
                position: absolute;
                height: 100%;
                width: 100%;
                top : 5%;
                left : 98%;
            }

            #event1imgCalendar{
                background-image: url('../assets/img/calendrier_event.png');
                background-size: contain;
                background-repeat: no-repeat;
                width: 30%;
                height: 100%;
                top: 0%;
                left: -25%;
                position: absolute;
            }

            #eventDate{
                font-family: "futura-book";
                position: absolute;
                top:0%;
                left:20%;
                font-size: 150%;
            }

            #event1plus{
                font-family: "futura-light-oblique";
                position: absolute;
                top: 140%;
                left:-25%;
                font-size: 150%;
                width: 200%;
            }

            #event1img{
                position : absolute;
                background:url('../assets/img/img1-event.jpg');
                background-size: contain;
                background-repeat: no-repeat;
                left: 10%;
                top: 31%;
                width: 61%;
                height: 66%;
            }

            #event1deco{
                position: absolute;
                width: 3%;
                height: 89%;
                top : 0%;
                left : 100%;
                background-color: rgb(166, 43, 72);
            }

            #event1H{
                position : relative;
                top : 26%;
                left: -25%;
                width: 200%;
                height: 5%;
                text-align: left;
                font-family: "futura-heavy";
                font-size: 250%;
            }
            #event1Pcolor{
                font-family: "futura-book";
                position : absolute;
                text-align: right;
                top : 122%;
                left : -38%;
                width: 200%;
                font-size: 150%;
            }

            #event1P{
                font-family: "futura-book";
                text-align: right;
                position : absolute;
                top : 165%;
                left: -40%;
                width: 200%;
                height: 10%;
                font-size: 150%;
            }
            #img1event{
                        position: relative;
                        height: 22%;
                        width: 44%;
                        top : 30%;
                        left : 5%;
                    }

                    #event2left{
                        position: absolute;
                        height: 100%;
                        width: 40%;
                        top : 0%;
                        left : 4%;
                    }

                    #event2right{
                        position: absolute;
                        height: 47%;
                        width: 65%;
                        top : 0%;
                        left : 43%;
                    }

                    #event2imgCalendar{
                        background-image: url('../assets/img/calendrier_event.png');
                        background-size: contain;
                        background-repeat: no-repeat;
                        width: 50%;
                        height: 100%;
                        top: 0%;
                        left: -32%;
                        position: absolute;
                    }

                    #event2Date{
                        font-family: "futura-book";
                        position: absolute;
                        text-align: right;
                        top:10%;
                        left:42%;
                        font-size: 150%;
                    }

                    #event2plus{
                        font-family: "futura-light-oblique";
                        position: absolute;
                        top: 130%;
                        left: -20%;
                        width: 120%;
                    }

                    #event2img{
                        position : absolute;
                        background:url('../assets/img/img2-event.jpg');
                        background-size: contain;
                        background-repeat: no-repeat;
                        left:21%;
                        top:47%;
                        width:65%;
                        height: 65%;
                    }

                    #event2deco{
                        position: absolute;
                        width: 1.5%;
                        height: 107%;
                        top : 0%;
                        left : 40%;
                        background-color: rgb(166, 43, 72);
                    }

                    #event2H{
                        position : absolute;
                        top : 15%;
                        left: 0%;
                        width: 100%;
                        height: 5%;
                        text-align: left;
                        font-family: "futura-heavy";
                        font-size: 200%;
                    }
                    #event2Pcolor{
                        font-family: "futura-book";
                        position : absolute;
                        text-align: left;
                        top : 75%;
                        left : 0%;
                        font-size: 150%;
                    }

                    #event2P{
                        font-family: "futura-book";
                        text-align: left;
                        position : absolute;
                        top : 117%;
                        left: 0%;
                        width: 100%;
                        height: 10%;
                        font-size: 150%;
                    }
</style>
