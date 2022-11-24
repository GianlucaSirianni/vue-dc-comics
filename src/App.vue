<template>
  <div id="app">
    <HeaderComp/>
    <JumbotronComp/>
    <ContentComp/>
    <MainNav/>
    <FooterNav/>
    <FooterSocial/>

  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue'
import JumbotronComp from './components/JumbotronComp.vue'
import ContentComp from './components/ContentComp.vue'
import MainNav from './components/MainNav.vue'
import FooterNav from './components/FooterNav.vue'
import FooterSocial from './components/FooterSocial.vue'





export default {
  name: 'App',
  components: {
    HeaderComp,
    JumbotronComp,
    ContentComp,
    MainNav,
    FooterNav,
    FooterSocial


  }
}
</script>

<style lang="scss">
#app {
  width: 100vw;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
