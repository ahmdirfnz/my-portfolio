<template>
<b-navbar :fixed-top="false" :transparent="false" type="is-dark">
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
      Home
    </b-navbar-item>
    <b-navbar-item href="#">
      Skills
    </b-navbar-item>
    <b-navbar-item href="#">
      About
    </b-navbar-item>
  </template>
  <template #end>
            <b-navbar-item tag="div">
                <div class="buttons">
                    <a class="button is-primary">
                        <strong>Subscribe</strong>
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

<style>
.nav {
    font-size: 20px;
}

nav.navbar.is-fixed-top {
  background: transparent;
}
</style>