<template>
  <header>
      <h1>{{title}}</h1>
  </header>
</template>

<script>
export default {
  name: 'appHeader',
  data () {
    return {
      title: 'Title'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

header {
    background: #34495e;
    color: #fff;
}

h1, h2 {
  font-weight: normal;
  margin: 0;
}


</style>
