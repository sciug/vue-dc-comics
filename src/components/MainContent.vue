<template>
  <div class="content">
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

</style>