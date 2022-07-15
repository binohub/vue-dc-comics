<template>


  <div id="MainSite" class="d-flex">
    <div id="divContent">
      <h5 id="hContent"> -- Content Goes Here -- </h5>
    </div>
    <div id="divMerch"></div>
    <div id="divInfo"></div>
  </div>



</template>

<script>


export default {

}
</script>

<style lang="scss" scoped>
@import "../styles/var.scss";

#MainSite {
  height: 80vh;
  background-color: $bgDarkBlue;
  flex-direction: column;
}

#divContent {
  height: 15vh;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: space-around;

  background-color: black;
  color: white;
}

#divMerch {
  height: 15vh;
  width: 100%;
  background-color: orange;
}

#divInfo {
  height: 50vh;
  width: 100%;
  background-color: yellow;
}

#hContent {
  font-weight: 400;
  font-size: 1.8rem;
}
</style>
