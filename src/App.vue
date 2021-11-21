<template>
  <div id="app" class="bg-img">
    <Navbar />
    <!-- <Home msg="Hi I am irfanz"/> -->
  </div>
</template>

<script>
// import Home from './components/Home.vue'
import Navbar from './components/Navbar.vue'

export default {
  name: 'App',
  components: {
    Navbar
    // Home    
  }
}
</script>

<style>

body, html {
  height: 100%;
  padding-top: 0px !important;
}

#app {
  margin: 0px;
  height: 100%;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.bg-img {
  background-image: url("./assets/sandWallpaper.jpg");
  background-position: center;
  background-repeat:  no-repeat;
  background-size:  cover;
  height: 100%;
}
</style>
