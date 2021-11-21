<template>
<div class="box">
  I'm in a box.
</div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.box-margin {
  margin-top: 10px;
}

.box {
  padding: 30px
}

</style>
