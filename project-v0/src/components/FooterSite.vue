<template>
  <div id="FooterSite" class="d-flex justify-content-around align-items-center">
    <button id="btnSign" type="button" class="btn btn-outline-primary">SIGN-UP NOW!</button>
    <h5 id="hFollow">FOLLOW US</h5>
    
  </div>
</template>

<script>
export default {
} 
</script>

<style lang="scss" scoped>
@import "../styles/var.scss"; 

  #FooterSite{
    height: 10vh;
    background-color: darkgray;
  }
  #btnSign{
    font-weight: 900;
  }
  #hFollow{
    font-weight: 800;
    font-size: 1rem;
  }


</style>