<template>
  <div class="d-flex justify-content-around align-items-center">
    <img class="img-fluid" src="../assets/img/dc-logo-bg.png" alt="logo">
    <nav>
      <ul>
        <li>
          Home
        </li>
        <li class="active">
          Home
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
  img{
    height: 5rem;
    margin: 1rem;
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
    }
    li.active{
      background-color: $bgActive;
    }
    li:hover{
      background-color: $bgActive;
    }
</style>
