<template>


  <div id="MainSite" class="d-flex">
    <div id="divContent">
      <h5 id="hContent"> -- Content Goes Here -- </h5>
    </div>
    <div id="divMerch">
      <ul class="gap-5">
        <li>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
          Digital Comics
        </li>
        <li>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
          Digital Comics
        </li>
        <li>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
          Digital Comics
        </li>
        <li>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
          Digital Comics
        </li>
        <li>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
          Digital Comics
        </li>
      </ul>
    </div>
    <div id="divInfo">
      <div id="titleInfo">
        <h5 class="hInfo">DC COMICS</h5>
        <ul>
          <li>Characters</li>
          <li>Characters</li>
          <li>Characters</li>
          <li>Characters</li>
          <li>Characters</li>
          <li>Characters</li>
        </ul>
      </div>
      <div id="titleInfo">
        <h5 class="hInfo">HELP</h5>
        <ul>
          <li>Characters</li>
          <li>Characters</li>
        </ul>
      </div>
    </div>
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
  background-color: #0282f9;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-around;

}

#divMerch ul {
  text-decoration: none;
  list-style-type: none;
  display: flex;
  margin: 0;
  padding: 0;
}

#divInfo {
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  gap: 2rem;
  align-items: flex-start;
  justify-content: center;

  background-image: url("../assets/img/footer-bg.jpg");
}

#titleInfo {
  width: 200px;
  text-align: center;
  color: white;
  font-weight: 800;
}

li {
  font-weight: bold;
  padding: .5rem;
  font-size: .8rem;
  transition: .2s;
}

li img {
  height: 80px;
  padding: .8rem;
}


#divInfo {
  height: 50vh;
  width: 100%;
}

#divInfo ul {
  text-decoration: none;
  list-style-type: none;
  margin: 0;
  padding: 0;
}


#hContent {
  font-weight: 400;
  font-size: 1.8rem;
}
</style>
