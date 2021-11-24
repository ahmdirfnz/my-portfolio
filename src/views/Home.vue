<template>
<!-- <div class="box">
  I'm in a box.
</div> -->

<!-- <div class="tile is-ancestor">
  <div class="tile is-child notification is-warning">
    Salam... 
  </div>
  <div class="tile is-child notification is-primary">
    Perkenalan
  </div>
</div> -->
<div class="box">
<section class="section is-medium box-margin">
  <h1 class="title">Hi, Im Irfanz</h1>
  <h2 class="subtitle">
    Currently Learning About Software Development
  </h2>
</section>
</div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.box-margin {
  margin-top: 35px;
}

.box {
  /* padding: ; */
  background: transparent;
}

h1 {
  color: white;
}

h2 {
  color: #e7e7e7;
}

</style>
