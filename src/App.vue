<template>
  <div id="app">
    <img src="./assets/logo.png">
    <h1>{{msg}}</h1>
    <firstcompionent></firstcompionent>
  </div>
</template>

<script>
  import firstcompionent from './components/firstcomponent.vue'

  export default {
    data(){
      return {
        msg: 'Hello Vue!'
      }
    },
    components: { firstcompionent}
  }
</script>

<style>
  body{
    font-family: Helvetica,sans-serif;
  }
</style>
