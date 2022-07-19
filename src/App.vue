<template>
  <div id="app">
    <HeaderSite/>
    <MainSite />
    <FooterSite />
  </div>
</template>

<script>
import MainSite from './components/MainSite.vue'
import HeaderSite from './components/HeaderSite.vue'
import FooterSite from './components/FooterSite.vue'

export default {
  name: 'App',
  components: {
    MainSite,
    HeaderSite,
    FooterSite,
  }
}
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap.scss";
@import "./assets/styles/var.scss";
  body{
    background-color: $mainBgColor;
    color: whitesmoke;
    letter-spacing: 1px;
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
  }
  .uwuContainer{
    padding: .2rem;
    width: 68%;
    margin: 0 auto;
  }
</style>
