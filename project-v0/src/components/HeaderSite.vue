<template>
  <div id="HeaderSite" class="d-flex justify-content-around align-items-center">
    <img class="img-fluid" src="../assets/img/dc-logo-bg.png" alt="logo">
    <nav>
      <ul>
        <li>
          Characters
        </li>
        <li class="active">
          Comics
        </li>
        <li>
          Home
        </li>
        <li>
          Home
        </li>
                <li>
          Home
        </li>
        <li class="">
          Home
        </li>
                <li>
          Home
        </li>
                <li>
          Home
        </li>
        <li class="">
          Home
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>
  @import "../styles/var.scss"; 

  #HeaderSite{
    height: 10vh;
  }
  img{
    height: 3rem;
    margin: 1rem;
    transition: .5s;
  }
    img:hover{
      filter: invert(2);
  }
  nav ul{
    text-decoration: none;
    list-style-type: none;
    display: flex;
    margin: 0;

  }
    li{
      font-weight: bold;
      cursor: pointer;
      padding: .8rem;
      font-size: .8rem;
      transition: .2s;
    }
    li.active{
      background-color: $bgActive;
      color: $bgDarkBlue;
      border-bottom: 1px solid limegreen;
    }
    li:hover{
      background-color: $bgActive;
      color: $bgDarkBlue;
      border-bottom: 1px solid $bgDarkBlue;
    }
</style>
