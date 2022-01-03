<template>
<h2>app component user name is mister : {{name}}</h2>
  <ComponentC />
</template>

<script>


import ComponentC from './components/ComponentC.vue'

export default {
  name: 'App',
  components: {
    ComponentC
  },
  data(){
    return {
    name: 'bulkin', 
    channel: 'bulkindrive'
    }
  },
  provide(){
    return{
      username: this.name, 
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
