<template>
  <div id="app">
    <Long title='Conversor de longitud' btn1='Convertir' btn2='Limpiar'/> 
    <br>
    <masa title='Conversor de masa' /><br>
    <Almacenamiento title='Conversor de Almacenamiento'/>
    <br>
    <monedas title='Coversor de monedas'/>
  </div>
</template>

<script>

import Long from './components/long.vue'
import Masa from './components/masa.vue'
import Almacenamiento from './components/Almacenamiento.vue'
import monedas from './components/monedas.vue'


export default {
  name: 'App',
  components: {
    Long,
    Masa,
    Almacenamiento,
    monedas
  }

    }
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
