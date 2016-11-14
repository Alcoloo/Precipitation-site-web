<template>
  <div id="backgrounds">
    <div class="bottom1"></div>
    <div class="top1"></div>
    <div class="bottom2"></div>
    <div class="top2"></div>
    <div class="bottom3"></div>
    <div class="top3"></div>
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
      visible : true
    }
  },
  methods: {
    toggle : function(){
      this.visible = !this.visible;
    }
  }
}
</script>

<style scoped>
.fade-enter-active, .fade-leave-active{
  transition: all .5s;
}

.fade-enter, .fader-leave-active{
  opacity: 0;
  transform: translateX(30px);
}
.top1{
  background: url('../assets/img/top1.png') no-repeat left top;
  -webkit-background-size: contain;
  -moz-background-size: contain;
  -o-background-size: contain;
  background-size: contain;
  position:absolute;
  height:50%;
  width: 100%;
  top :-7%;
  left :0px;
  transition: all 2s ease-in-out;
  transform-origin:center;
  pointer-events:none;
  z-index: -1;
  -webkit-transform:translateZ(2px);
}

.top2{
  background: url('../assets/img/top2.png') no-repeat left top;
  -webkit-background-size: contain;
  -moz-background-size: contain;
  -o-background-size: contain;
  background-size: contain;
  position:absolute;
  height:50%;
  width: 100%;
  top :-7%;
  left :0px;
  transition: all 2s ease-in-out;
  transform-origin:center;
  pointer-events:none;
  z-index: -3;
  -webkit-transform:translateZ(1px);
}
.top3{
  background: url('../assets/img/top3.png') no-repeat left top;
  -webkit-background-size: contain;
  -moz-background-size: contain;
  -o-background-size: contain;
  background-size: contain;
  position:absolute;
  height:50%;
  width: 100%;
  top :-7%;
  left :0px;
  transition: all 2s ease-in-out;
  transform-origin:center;
  pointer-events:none;
  z-index: -5;
  -webkit-transform:translateZ(0px);
}
.bottom1{
  background: url('../assets/img/bottom1.png') no-repeat right center fixed;
  -webkit-background-size: contain;
  -moz-background-size: contain;
  -o-background-size: contain;
  background-size: contain;
  float:left;
  position:absolute;
  height:100%;
  width: 720px;
  top :0px;
  right :0px;
  transition: all 0.5s ease-in-out;
  transform-origin:center ;
  pointer-events:none;
  z-index: 0;
  -webkit-transform:translateZ(2px);
}
.bottom2{
  background: url('../assets/img/bottom2.png') no-repeat right center fixed;
  -webkit-background-size: contain;
  -moz-background-size: contain;
  -o-background-size: contain;
  background-size: contain;
  float:right;
  position:absolute;
  height:100%;
  width: 100%;
  top :0px;
  left :0px;
  transition: all 0.5s ease-in-out;
  transform-origin:center ;
  pointer-events:none;
  z-index: -2;
  -webkit-transform:translateZ(1px);
}
.bottom3{
  background: url('../assets/img/bottom3.png') no-repeat right center fixed;
  -webkit-background-size: contain;
  -moz-background-size: contain;
  -o-background-size: contain;
  background-size: contain;
  float:right;
  position:absolute;
  height:100%;
  width: 100%;
  top :0px;
  left :0px;
  transition: all 0.5s ease-in-out;
  transform-origin:center ;
  pointer-events:none;
  z-index: -4;
  -webkit-transform:translateZ(0px);
}
</style>
