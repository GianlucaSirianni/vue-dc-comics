<template>
  <div id="app">

    <HeaderComp/>

    <ContentComp/>

    <MainNav/>

    <FooterNav/>

    <FooterSocial/>



  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue'
import ContentComp from './components/ContentComp.vue'
import MainNav from './components/MainNav.vue'
import FooterNav from './components/FooterNav.vue'
import FooterSocial from './components/FooterSocial.vue'

export default {
  name: 'App',
  components: {
    HeaderComp,
    ContentComp,
    MainNav,
    FooterNav,
    FooterSocial
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  width: 100vw;

}
</style>
