<template>
<greet name="Bruce" heroName="Batmen"/>
<greet name="John" heroName="rock"/>
<greet name="Seb" heroName="F1champ"/>
<greet :name="name" :heroName="channel"/>
<Article title="Article Title" :likes="50" :isPublished="true"/>
</template>

<script>

import greet from './components/Greet.vue'
import Article from './components/Article.vue'

export default {
  name: 'App',
  components: {
    greet,
    Article
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
