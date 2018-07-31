<template>
  <div id="app">
    <img src="./assets/logo.png">
    <!--<router-view name="left" style="float:left;width:50%;height:300px;background-color:#ccc;"></router-view>-->
    <router-link to="/">Home</router-link>|
    <router-link to="/params/198/jspang website is very good">params</router-link>|
    <router-link to="/goHome">goHome</router-link>|
    <router-link to="/goParams/198/jspang website is very good">goParams</router-link>|
    <!--<router-link to="/goParams/">goParams</router-link>|-->
    <router-view></router-view>
    <!--<router-view name="right" style="float:left;width:50%;height:300px;background-color:#c0c;"></router-view>-->
  </div>
</template>

<script>
export default {
  name: 'App'
}
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
