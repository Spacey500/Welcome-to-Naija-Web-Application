<template>
  <Navigation class="no-scroll"/>
  <router-view/>
</template>

<script>
import Navigation from './components/Navigation.vue'
export default {
  components: { Navigation},
}
</script>

<style>
#app {
  background-color:#041010;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  color:#FCFFFC;
}

*{
  margin:0;
}

header.no-scroll{
  overflow: hidden;
  position: fixed !important;
}

</style>
