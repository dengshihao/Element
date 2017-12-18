<template>
  <div id="app">
    <v-header></v-header>
    <v-nav></v-nav>
    <router-view/>
  </div>
</template>

<script>
import VHeader from './components/layout/header.vue'
import VNav from './components/layout/nav.vue'
export default {
  name: 'app',
  components:{
    VHeader,VNav
  }
}
</script>

<style lang="scss">
#app{
  position: relative;
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
  padding-top: 80px;
  height: 100%;
}
</style>
