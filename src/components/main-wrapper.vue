<template>
  <div class="main-wrapper">
    <filters></filters>
  </div>
</template>

<script>
import Filters from './filters.vue';

export default {
  name: 'main-wrapper',
  data () {
    return {
      
    }
  },
  components: {
    Filters,
  }
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
.main-wrapper {
  padding: 30px;
}
</style>
