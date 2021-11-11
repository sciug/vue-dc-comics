<template>
  <div id="app">
    <SiteHeader/>
    <MainContent/>
   
  </div>
</template>

<script>
import SiteHeader from "./components/SiteHeader.vue";
import MainContent from "./components/MainContent.vue";

export default {
  name: "App",
  components: {
  SiteHeader,
  MainContent
  }
};
</script>

<style lang="scss">
@import url('./assets/scss/common.scss');
.main{
  height: 800px;
  background: rebeccapurple;
}
</style>
