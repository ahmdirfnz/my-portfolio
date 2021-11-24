<template>
<b-navbar :fixed-top="false" :transparent="true" type="is-dark">
  <template #brand>
    <b-navbar-item tag="router-link" :to="{ path: '/'}">
      <img
        src="../assets/terminal.jpg"
        alt="Terminal Image"
      >
    </b-navbar-item>
  </template> 
  <template #start>
    <b-navbar-item>
      <router-link to="/">Home</router-link>
    </b-navbar-item>
    <b-navbar-item>
      <router-link to="/projects">Projects</router-link>
    </b-navbar-item>
    <b-navbar-item>
      <router-link to="/about">About</router-link>
    </b-navbar-item>
    <router-view />
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
</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style scoped>

nav.navbar.is-fixed-top {
  background: transparent;
}
</style>