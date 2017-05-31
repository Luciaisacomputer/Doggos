<template>
  <footer>
      <p>{{footerText}}</p>
  </footer>
</template>

<script>
export default {
  name: 'appFooter',
  data () {
    return {
      footerText: 'This is the footer'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

footer {
    background: #34495e;
    color: #fff;
}

h1, h2 {
  font-weight: normal;
}


</style>
