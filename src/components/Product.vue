<template>
  <div class="card">
      <img :src="thumb" :alt="series">
      <h3>{{series}}</h3>
  </div>
</template>

<script>
export default {
    props:{
        thumb: String,
        series: String
    }

}
</script>

<style lang="scss">
.card{
    padding: .8rem;
    img{
        height:calc(202.55px - .8rem) ;
        width: 100%;
        object-fit: cover;
    }
    h3{
        font-weight: 200;
        margin-top: .8rem;
        font-family: Arial, Helvetica, sans-serif;
        text-transform: uppercase;
        font-size: .8rem;
    }
}

</style>