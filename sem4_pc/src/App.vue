<template>
  <div id="app">
    <Long title='Conversor de longitud' btn1='Convertir' btn2='Limpiar'/> 
    <br><br>
    <masa title='Conversor de masa' /><br><br>
    <Almacenamiento title='Conversor de Almacenamiento'/>
    <br><br>
    <monedas title='Conversor de monedas'/>
    <br><br>
    <Tiempo title='Conversor de tiempo'/>
  </div>
</template>

<script>

import Long from './components/long.vue'
import Masa from './components/masa.vue'
import Almacenamiento from './components/Almacenamiento.vue'
import monedas from './components/monedas.vue'
import Tiempo from './components/Tiempo.vue'


export default {
  name: 'App',
  components: {
    Long,
    Masa,
    Almacenamiento,
    monedas,
    Tiempo
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
