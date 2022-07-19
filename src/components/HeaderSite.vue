<template>
  <div id="headerSite" class="d-flex justify-content-between align-items-center">

    <div class="uwuContainer">
      <div id="headerLogo">
        <img class="img-fluid" src="../assets/img/dc-logo-bg.png" alt="dc comics logo">
      </div>

      <nav id="headerNav">
        <ul>
          <li v-for="(lindex, index) in navLists" :key="index" class="lindexHeader">

            <a :href="lindex.url">
              {{ lindex.text }}
            </a>

          </li>
        </ul>
      </nav>
    </div>


  </div>
</template>

<script>
export default {
  data: function () {
    return {
      navLists: [
        {
          text: "Characters",
          url: "#"
        },
        {
          text: "Comics",
          url: "#"
        },
        {
          text: "Movies",
          url: "#"
        },
        {
          text: "Tv",
          url: "#"
        },
        {
          text: "Games",
          url: "#"
        },
        {
          text: "Collectibles",
          url: "#"
        },
        {
          text: "Videos",
          url: "#"
        },
        {
          text: "Fans",
          url: "#"
        },
        {
          text: "News",
          url: "#"
        },
      ],
    }
  }
}
</script>

<style lang="scss" scoped>
@import "../styles/var.scss";

#headerSite { 
  background-color: white;
  height: 10vh;
  div.uwuContainer {
    display: flex;
  }

  #headerLogo {
    width: 30%;

    img {
      height: 3rem;
    }
  }

  #headerNav {
    width: 70%;

    ul {
      list-style-type: none;
      display: flex;

      align-items: center;
      // to center ul items
      height: 100%;
    }

    li {
      display: inline-block;
      padding-right: 2rem;
      font-size: .8rem;
    }
      a{
        text-transform: uppercase;
        text-decoration: none;
        color: black;
      }
  }
}


// li.active {
//   background-color: $bgActive;
//   color: $bgDarkBlue;
//   border-bottom: 1px solid limegreen;
// }

// li:hover {
//   background-color: $bgActive;
//   color: $bgDarkBlue;
//   border-bottom: 1px solid $bgDarkBlue;
// }
</style>
