<template>
<greet name="Bruce" heroName="Batmen"/>
<greet name="John" heroName="rock"/>
<greet name="Seb" heroName="F1champ"/>
<greet :name="name" :heroName="channel"/>
</template>

<script>

import greet from './components/Greet.vue'

export default {
  name: 'App',
  components: {
    greet,
  },
  data(){
    return {
    name: 'bulkin',
    channel: 'bulkindrive'
    }
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
