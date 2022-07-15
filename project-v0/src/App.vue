<template>
  <div id="app">
    <HeaderSite />
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
    @import "./styles/var.scss"; 

    body{
      background-color: $bg-light ;
    }



    </style>
