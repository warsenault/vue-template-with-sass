<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
  import 'font-awesome/css/font-awesome.css';
  import './assets/bulma.sass';

  export default {
    name: 'app',
  };
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
