<script>
import AppTitle from './components/AppTitle.vue'

export default {
 data() {
  return {
    saluti: "Ciao a tutti!!!"
  }
 },

 components:{
  titolo: AppTitle,
 }

}
</script>

<template>
  <h1 class="saluti">{{ saluti }}</h1>
  <titolo class="center" />
</template>

<style>
@import url('../src/assets/main.css');


</style>