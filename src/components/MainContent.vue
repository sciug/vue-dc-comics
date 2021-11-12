<template>
  <div class="content">
      <div class="jumbotron">
          <img src="../assets/img/jumbotron.jpg" alt="">
      </div>
      <div class="container padding">
           <h2> --yourcontent-- </h2>
      </div>
      <IconsSec/>
     
  </div>
</template>

<script>
import IconsSec from "../components/IconsSec.vue"
export default {
components:{
    IconsSec
}
}
</script>

<style lang="scss">
@import "../assets/scss/variables";
.content{
    color: white;
    background-color:$secondary_color;
}
.jumbotron{
    height: 400px;
    img{
        height: 100%;
        width: 100%;
        object-fit: cover;
        object-position: top;
    }
}
</style>