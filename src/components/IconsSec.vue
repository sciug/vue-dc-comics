<template>
<div class="background padding">
      <div class="container">
      <div class="icons">
          <div class="icon_container">
              <div class="icon">
                  <img src="../assets/img/buy-comics-digital-comics.png" alt="">
              </div>
              <p>Digital comics</p>

          </div>
           <div class="icon_container">
              <div class="icon">
                  <img src="../assets/img/buy-comics-merchandise.png" alt="">
              </div>
              <p>dc merchandise</p>

          </div>
           <div class="icon_container">
              <div class="icon">
                  <img src="../assets/img/buy-comics-subscriptions.png" alt="">
              </div>
              <p>subscription</p>

          </div>
           <div class="icon_container">
              <div class="icon">
                  <img src="../assets/img/buy-comics-shop-locator.png" alt="">
              </div>
              <p>comic shop locator</p>

          </div>
           <div class="icon_container">
              <div class="icon">
                  <img src="../assets/img/buy-dc-power-visa.svg" alt="">
              </div>
              <p>dc power visa</p>

          </div>
      </div>

  </div>
</div>

</template>

<script>
export default {

}
</script>

<style lang="scss">
@import "../assets/scss/variables";

.background{
    background-color: $base_color;}
.icons{
    width: 100%;
    display: flex;
    .icon{
        height: 40px;
        img{
            height: 100%;
        }
    }
    
}
.icon_container{
    width: calc(100% / 5);
    display: flex;
    align-items: center;
    p{
        margin-left: .5rem;
        text-transform: uppercase;
        font-size: .8rem;
        letter-spacing: 1px;
        font-family: Arial, Helvetica, sans-serif;
    }
}

</style>