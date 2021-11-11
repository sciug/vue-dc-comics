<template>
  <div class="container d-flex space_between_align_center site_header">
      <div class="logo">
          <img src="../assets/img/dc-logo.png" alt="dc logo">
      </div>
      <nav class="menu">
          <a href="#">Characters</a>
          <a href="#" class="active">Comics</a>
          <a href="#">Movies</a>
          <a href="#">Tv</a>
          <a href="#">Games</a>
          <a href="#">collectibles</a>
          <a href="#">videos</a>
          <a href="#">fans</a>
          <a href="#">news</a>
          <a href="#">shop</a>

          

      </nav>

  </div>
</template>

<script>
export default {

}
</script>

<style  lang="scss">
@import "../assets/scss/variables";
.site_header{
    padding-top: 1.5rem;
}
.logo{
    width: 70px;
    padding-bottom: .8rem;
    img{
        width: 100%;
    }
}
.menu{
    padding-top: 1rem;
display:flex;
    a{
        text-decoration: none;

        color:$third_color;
        text-transform: uppercase;
        font-weight: 800;
        font-size: .7em;
        margin: 0 .7rem;
        &.active{
        color: $base_color;
        border-bottom: 5px solid $base_color;
    }
    }
    
}


</style>