<template>
  <div id="app">
    <main-index/>
  </div>
</template>

<script>
import Index from './views/IndexMain.vue'
import axios from "axios";

export default {
  components: {
     'main-index' : Index
      },
  name: 'App',

  data() {
    return {
      generation: [],
    }
  },

  mounted() {
    axios
    .get ("https://pokeapi.co/api/v2/generation")
    .then((response) => {
      console.log(response)
      response => this.generation = response.results
      console.log(this.generation)
    })
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
}
</style>
