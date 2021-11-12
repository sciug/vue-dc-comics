<template>
  <div class="background_footer">
      <div class="container d-flex space_between_align_center footer_container">
          <div class="footer_info d-flex">
              <div class="info_sec">
                  <div class="info_sec_top">
                      <h4>DC comics</h4>
                    <ul>
                        <li><a href="#">lorem</a></li>
                        <li><a href="#">lorem</a></li>
                        <li><a href="#">lorem</a></li>
                        <li><a href="#">lorem</a></li>
                        <li><a href="#">lorem</a></li>
                        <li><a href="#">lorem</a></li>
                        <li><a href="#">lorem</a></li>

                    </ul>

                  </div>
                  <div class="info_sec_bottom">
                        <h4>DC comics</h4>
                    <ul>
                        <li><a href="#">lorem</a></li>
                        <li><a href="#">lorem</a></li>
                        

                    </ul>
                  </div>
              </div>
              <div class="info_sec">
                    <h4>DC comics</h4>
                    <ul>
                        <li><a href="#">lorem</a></li>
                        <li><a href="#">lorem</a></li>
                        <li><a href="#">lorem</a></li>
                        <li><a href="#">lorem</a></li>
                        <li><a href="#">lorem</a></li>
                        <li><a href="#">lorem</a></li>
                        <li><a href="#">lorem</a></li>

                    </ul>
              </div>
              <div class="info_sec">
                    <h4>DC comics</h4>
                    <ul>
                        <li><a href="#">lorem</a></li>
                        <li><a href="#">lorem</a></li>
                        <li><a href="#">lorem</a></li>
                        <li><a href="#">lorem</a></li>
                        <li><a href="#">lorem</a></li>
                        <li><a href="#">lorem</a></li>
                        <li><a href="#">lorem</a></li>

                    </ul>
              </div>
          </div>
          <div class="footer_logo_png">
              <img src="../assets/img/dc-logo-bg.png" alt="">
          </div>

      </div>
      <FooterSignUp/>
  </div>
</template>

<script>
import FooterSignUp from '../components/FooterSignUp.vue'
export default {
    components:{
        FooterSignUp
    }

}
</script>

<style lang="scss">
.background_footer{
    height: 350px;
    background-size: cover;
    background-image: url('../assets/img/footer-bg.jpg');
  }

.footer_container{
    height: 100%;
    
}
.footer_info,
.footer_logo_png{
    width: 45%;
}
.info_sec{
    width: 25%;
    margin-top: 2rem;
    .info_sec_bottom{
        margin-top: 1.5rem;
    }
    h4{
        margin-bottom: 1rem;
        color: white;
        font-size: 1.1rem;
        text-transform: uppercase;
    }
    ul{
        list-style: none;
        li{
            a{
             text-decoration: none;
            color: rgba(182, 181, 181, 0.664);
            font-size: .9rem;
            font-weight: 500;
            text-transform: capitalize;
            letter-spacing: .5px;

        }
           
        }
    }
}
.footer_logo_png{
    height: 100%;
    img{
        height: 100%;
        width: 100%;
        object-fit: cover;
    }
}


</style>