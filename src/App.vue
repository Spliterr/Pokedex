<template>
  <div id="app">
    <main-index/>
  </div>
</template>

<script>
import Index from './components/views/IndexMain.vue'

export default {
  components: {
     'main-index' : Index
      },
  name: 'App',
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
