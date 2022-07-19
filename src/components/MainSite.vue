<template>
  <div id="MainSite" class="">

    <div id="divContent">

      <div id="divContentUp">
        <h5 class="jumboTxt">CURRENT SERIES</h5>
      </div>

      <div id="divContentDown">

        <div id="dcContainer" class="uwuContainer d-flex justify-content-center flex-wrap">

          <div class="card-container" v-for="(cardi, index) in dc" :key="index">
            <div class="image-container">
              <img class="img-fluid" :src="cardi.thumb" alt="element.series">
            </div>
            <div class="title-container">
              <h3 class="fw-bold">
                {{ cardi.series }}
              </h3>
            </div>
          </div>
          <button id="btnLoad" type="button" class="btn btn-primary">LOAD MORE!</button>

        </div>

      </div>

      <div id="divMerch">
        <div class="uwuContainer">
          <ul class="justify-content-between">
            <li>
              <img src="../assets/img/buy-comics-digital-comics.png" alt="">
              Digital Comics
            </li>
            <li>
              <img src="../assets/img/buy-comics-merchandise.png" alt="">
              Merchandise
            </li>
            <li>
              <img src="../assets/img/buy-comics-shop-locator.png" alt="">
              Shop Locator
            </li>
            <li>
              <img src="../assets/img/buy-comics-subscriptions.png" alt="">
              Buy Comics Sub
            </li>
            <li>
              <img src="../assets/img/buy-dc-power-visa.svg" alt="">
              Visa
            </li>
          </ul>
        </div>
      </div>

      <div id="divInfo">
        <div class="uwuContainer">

          <div id="titleInfoBig" class="titleInfo">
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

          <div id="titleInfoSmall" class="titleInfo">
            <h5 class="hInfo">HELP</h5>
            <ul>
              <li>Characters</li>
              <li>Characters</li>
            </ul>
          </div>

        </div>


      </div>


    </div>

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
  #divContent {

    #divContentUp {
      position: relative;

      height: 40vh;
      background-image: url('../assets/img/jumbotron.jpg');

      .jumboTxt {
        position: absolute;
        bottom: -25px;
        left: 300px;

        background-color: #0282f9;
        display: inline-block;
        padding: .8rem;
      }
    }

    #divContentDown {
      padding: 5rem 0;

      .card-container {
        width: calc(100% / 4);
      }

      .image-container {
        height: 80%;

        img {
          width: 100%;
          height: 100%;
          object-fit: contain;
        }
      }

      .title-container {
        height: 20%;

        display: flex;
        align-items: center;
        justify-content: center;

        h3 {
          font-size: .8rem;
        }
      }

      #btnLoad {
        ont-size: 1.5rem;
      }

    }

    #divMerch {
      width: 100%;
      padding: 1rem 0;
      background-color: #0282f9;

      ul {
          text-decoration: none;
          list-style-type: none;
          display: flex;
          margin: 0;
          padding: 0;
        
          li img {
            height: 80px;
            padding: 1.5rem;
          }
        }
      
    }

    #divInfo {
      background-image: url("../assets/img/footer-bg.jpg");
      padding: 2rem 0;
      
      .titleInfo {
        text-align: start;
        width: 250px;
        padding: .8rem 0;
      }
      ul {
        text-decoration: none;
        list-style-type: none;
        margin: 0;
        padding: 0;
        li {
        font-weight: bold;
        padding: .5rem 0;
        font-size: .8rem;
        }
      }
      



    }


  }
}
</style>
