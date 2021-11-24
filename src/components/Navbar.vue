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
    <b-navbar-item href="#">
      <h3>Home</h3>
    </b-navbar-item>
    <b-navbar-item href="#">
      <h3>Skills</h3>
    </b-navbar-item>
    <b-navbar-item href="#">
      About
    </b-navbar-item>
    <b-navbar-item href="#">
      Projects
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