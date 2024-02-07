<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default {
 data() {
  return {
    saluti: "CIAO A TUTTI!!!"
  }
 },

 components:{
   AppTitle,
  immagineJumbo: AppHero
 }

}
</script>

<template>
  <h1 class="saluti">{{ saluti }}</h1>
  <AppTitle class="center" />
  <immagineJumbo/>
</template>

<style>
/*@import url('../src/assets/main.css');*/
.center {
    text-align: center;
}
</style>