<template>
  <div class="jumbotron">
    <headnav />
    <div class="main">
       <part1 />
       <part2 />
       <part3 />
    </div>
      <botnav/>
  </div>
</template>
<script>
import headnav from './components/nav.vue'
import part3 from "./components/part3.vue";
import part2 from "./components/part2.vue";
import Part1 from './components/part1.vue';
import botnav from'./components/bottomnav.vue';
export default {
  name: 'App',
  props:['visible'],
  components: {
    headnav,
    part3,
    part2,
    Part1,
    botnav
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.jumbotron{
  margin-top: -60px;
}
</style>
