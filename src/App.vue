<template>
  <div id="app">
    <NavBar/>
    <router-view/>
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue"
export default {
  name: 'app',
  data() {
    return {
    };
  },
  components:{
    NavBar
  }
}
</script>


<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
  -ms-flex-align: center;
  align-items: center;
}
.centertext {
  text-align: center;
}
</style>
