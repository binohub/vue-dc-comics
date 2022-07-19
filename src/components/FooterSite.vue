<template>
  <div id="FooterSite" class="d-flex align-items-center">
    <div class="uwuContainer">

      <div id="footerBottom" class="d-flex justify-content-between align-items-center">
        <button id="btnSign" type="button" class="btn btn-outline-primary">SIGN-UP NOW!</button>
        <div id="sectionFollow" class="d-flex align-items-center gap-3">
          <h5 id="hFollow">FOLLOW US</h5>
          <img src="../assets/img/footer-facebook.png" alt="facebook">
          <img src="../assets/img/footer-twitter.png" alt="twitter">
          <img src="../assets/img/footer-youtube.png" alt="youtube">
          <img src="../assets/img/footer-pinterest.png" alt="pinterest">
          <img src="../assets/img/footer-periscope.png" alt="periscope">
        </div>
      </div>

    </div>
  </div>
</template>

<script>
export default {
} 
</script>

<style lang="scss">
@import "../styles/var.scss";


#FooterSite {
  height: 10vh;
  background-color: black;
  #btnSign {
    color: white;
    padding: .8rem;
    font-size: .8rem;
  }
  #sectionFollow {
    #hFollow {
      font-size: 1.5rem;
      // ! to align center
      margin: 0;
      color: blue;
    }
    img {
    transition: .2s;
    }
    img:hover {
    filter: sepia(2);
    cursor: pointer;
  }
  }


}








</style>