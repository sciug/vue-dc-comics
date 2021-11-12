<template>
  <div class="footer_sign_up_bg">
      <div class="container padding d-flex space_between_align_center">
          <button class="sign-up button">SIGN-UP NOW!</button>
          <ul class="social d-flex">
              <li class="follow">Follow Us</li>
              <li><a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a></li>
              <li><a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a></li>
              <li><a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a></li>
              <li><a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a></li>
               <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
              
          </ul>
      </div>

  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
@import "../assets/scss/variables";


.footer_sign_up_bg{
    background-color: $third_color;
}
.social{
    list-style: none;
    align-items: center;
    .follow{
        color:$base_color;
        font-size: 1.3rem;
        font-weight: bold;
        text-transform: uppercase;
    }
    li{
        margin: 0 1rem;
    }
}
.sign-up{
    border: 2px solid $base_color;
    background:none;
     padding: .5rem 1rem;
    
}
</style>