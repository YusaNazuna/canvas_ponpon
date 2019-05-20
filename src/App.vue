<template>
  <div id="app">
    <div class="bg"></div>
    <my-canvas class="canvas"/>
    <!-- <my-canvas class="canvas" v-for="i in 20" :key="i"/> -->
  </div>
</template>

<script>
import MyCanvas from './components/MyCanvas.vue'

export default {
  components: {
    MyCanvas
  }
}
</script>

<style>
html {
  background: #2F2F2F;
}
.bg {
  width: 98.5%;
  height: 94%;
  background: #efefef;
  position: absolute;
}
.canvas {
  position: absolute;
  top: 0;
}
</style>
