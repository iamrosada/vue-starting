<template>
  <div class="home">
    <h1>
      Bem vindo <span>{{myself}}</span>
    </h1>

  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
 data(){
  return {
    myself: "ROSADA 98xpace"
  }

 }
})
</script>

<style lang="css" scoped>
h1{
  font-size: 2rem;

}
span{
    color:#2d6cea
}
</style>
