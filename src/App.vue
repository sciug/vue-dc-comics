<template>
  <div id="app">
    <SiteHeader/>
    <MainContent/>
    <Footer/>
   
  </div>
</template>

<script>
import SiteHeader from "./components/SiteHeader.vue";
import MainContent from "./components/MainContent.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
  SiteHeader,
  MainContent,
  Footer
  }
};
</script>

<style lang="scss">
@import './assets/scss/common.scss';
.main{
  height: 800px;
  background: rebeccapurple;
}
</style>
