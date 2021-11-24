<template>
  <div id="app" class="bg-img">
    <b-navbar :fixed-top="false" :transparent="true" type="is-dark">
  <template #brand>
    <b-navbar-item tag="router-link" :to="{ path: '/'}">
      <img
        src="./assets/terminal.jpg"
        alt="Terminal Image"
      >
    </b-navbar-item>
  </template> 
  <template #start>
    <b-navbar-item href="#">
      <router-link to="/">Home</router-link>
    </b-navbar-item>
    <b-navbar-item href="#">
      <router-link to="/projects">Projects</router-link>
    </b-navbar-item>
    <b-navbar-item>
      <router-link to="/about">About</router-link>
    </b-navbar-item>
    
  </template>
  
  <template #end>
            <b-navbar-item tag="div">
                <div class="buttons">
                    <a class="button is-primary">
                        <strong>Contact Me</strong>
                    </a>
                    <a class="button is-light">
                        Say Hi
                    </a>
                </div>
            </b-navbar-item>
        </template>
        
</b-navbar>
<router-view />
  </div>
</template>

<script>
// import Navbar from './components/Navbar.vue'

export default {
  components: {
    // Navbar

  }
}
</script>

<style>
body, html {
  height: 100%;
}
#app {
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
