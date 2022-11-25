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

  font-family: Avenir, Helvetica, Arial, sans-serif;

}

body{
  margin: 0;
  box-sizing: border-box;
}


</style>
