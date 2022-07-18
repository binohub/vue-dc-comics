<template>


  <div id="MainSite" class="d-flex">
    <div id="divContent">
      <div id="divContentUp">
        <h5 class="jumboTxt">CURRENT SERIES</h5>
      </div>

      <div id="divContentDown">
        <div id="dcContainer" class="d-flex justify-content-between flex-wrap">

          <div class="card-container" v-for="(element, index) in dc" :key="index">
            <div class="image-container">
              <img class="img-fluid"
                :src="element.thumb"
                alt="element.series">
            </div>
            <div class="title-container">
              <h3 class="fw-bold">
                {{ element.series }}
              </h3>
            </div>
          </div>





        </div>
      </div>

    </div>


    <!-- 


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
    </div> -->
  </div>



</template>

<script>


export default {
  data: function () {
    return {
      dc: [
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
          "price": "$19.99",
          "series": "Action Comics",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
          "price": "$3.99",
          "series": "American Vampire 1976",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
          "price": "$16.99",
          "series": "Aquaman",
          "type": "graphic novel"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
          "price": "$2.99",
          "series": "Batgirl",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          "price": "$3.99",
          "series": "Batman",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          "price": "$2.99",
          "series": "Batman Beyond",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
          "price": "$3.99",
          "series": "Batman/Superman",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
          "price": "$4.99",
          "series": "Batman/Superman Annual",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
          "price": "$5.99",
          "series": "Batman: The Joker War Zone",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
          "price": "$6.99",
          "series": "Batman: Three Jokers",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
          "price": "$4.99",
          "series": "Batman: White Knight Presents: Harley Quinn",
          "type": "comic book"
        },
        {
          "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
          "price": "$16.99",
          "series": "Catwoman",
          "type": "graphic novel"
        },
      ],
    }


  }
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
  min-height: 40vh;
  width: 100%;
  display: flex;
  flex-direction: column;

  background-color: black;
  color: white;
}

#divContentUp {
  position: relative;

  min-height: 20vh;
  width: 100%;

  background-image: url('../assets/img/jumbotron.jpg');
  object-fit: cover;
  object-position: center;
}
#divContentUp .jumboTxt {
  position: absolute;
  bottom: -25px;
  left: 50px;
  background-color: #0282f9;
  display: inline-block;
  padding: .5rem;
  font-weight: bold;
}

#divContentDown {
  height: fit-content;
  width: 80%;
  margin: auto;

  font-size: 2rem;
  color: white;
}

#divContentDown div.card-container {
  height: 150px;
  width: calc(100% / 4);
  gap: .2rem;
  margin: .5rem 0;
}

#divContentDown div.image-container {
  height: 80%;
}

#divContentDown div.image-container img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

#divContentDown div.title-container {
  height: 20%;
  background-color: black;
}

#divContentDown div.title-container h3 {
  font-size: 1rem;
  text-align: center;
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
