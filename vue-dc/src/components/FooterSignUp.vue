<template>
  <div class="footer_sign_up_bg">
      <div class="container padding d-flex space_between_align_center">
          <button class="sign-up">SIGN-UP NOW!</button>
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
.footer_sign_up_bg{
    background-color: #303030;
}
.social{
    list-style: none;
    align-items: center;
    .follow{
        color:#0282f9;
        font-size: 1.3rem;
        font-weight: bold;
        text-transform: uppercase;
    }
    li{
        margin: 0 1rem;
    }
}
.sign-up{
    border: 2px solid #0282f9;
    color: white;
    background:none;
    padding: .5rem 1rem;
}
</style>