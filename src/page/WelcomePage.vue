<template>
  <div class="LandingPage">
    <MasterHeader msg="Better Together Competition"></MasterHeader>
    <IntermediateDivisionScoreboard></IntermediateDivisionScoreboard>
  </div>
</template>

<script>
import MasterHeader from '../components/MasterHeader.vue'

export default {
  name: 'LandingPage',
  props: {
    msg: String
  },
  components: {
    IntermediateDivisionScoreboard,
    MasterHeader
  },
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
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
