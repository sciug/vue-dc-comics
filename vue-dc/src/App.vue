<template>
  <div id="app">
    <SiteHeader/>
    <div class="main"></div>
    
  </div>
</template>

<script>
import SiteHeader from "./components/SiteHeader.vue";

export default {
  name: "App",
  components: {
  SiteHeader
  },
};
</script>

<style lang="scss">
@import url('./assets/scss/common.scss');
.main{
  height: 800px;
  background: rebeccapurple;
}
</style>
