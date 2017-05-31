<template>
  <div class="hello">
    <app-header></app-header>
    <div>
      <counter></counter>
    </div>
    <app-footer></app-footer>
  </div>
</template>

<script>

import appHeader from './Header.vue'
import appFooter from './Footer.vue'
import Counter from './Counter.vue'

export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: { appHeader, appFooter, Counter }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
