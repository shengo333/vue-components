<template>
  <Card />
  <Card>Card content</Card>
  <Card><h2>Card content</h2></Card>

  <Card><img src="https://picsum.photos/200"/> </Card>

  <Card>
    <template v-slot:header>
      <h3>Header</h3>
      </template>
    <template v-slot:default>
       <img src="https://picsum.photos/200"/>
    </template>
    <template v-slot:footer>
      <button>Vue Details</button>
    </template>
  </Card>

  
</template>

<script>


import Card from './components/Card.vue'

export default {
  name: 'App',
  components: {
    Card,
  },
  data(){
    return{
      name: '',
      
    }
  },
  methods:{

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
