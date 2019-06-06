<template>
  <div id="app"> 
    <Markup></Markup>
    <Slider></Slider>
  </div>  
</template>

<script>

import Markup from './components/Markup.vue'
import Slider from './components/Slider.vue'

export default {
  name: 'app',
  components: {
    Markup,
    Slider
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

}
</style>
