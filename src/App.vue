<template>
  <v-app>
    <v-main>
      <div class="FloatBanner"><img src="./assets/img/main/hyundaicard.png" alt="현대카드 이벤트"></div>
      <TopMenu />
      <Banner />
      <Notice />
      <Promo1 />
      <Promo2 />
      <Promo3 />
      <Bottom />
    </v-main>
  </v-app>
</template>
<style>
@import "./assets/css/base.css";
</style>
<script>
import TopMenu from "./components/TopMenu";
import Banner from "./components/Banner";
import Notice from "./components/Notice";
import Promo1 from "./components/Promo1";
import Promo2 from "./components/Promo2";
import Promo3 from "./components/Promo3";
import Bottom from "./components/Bottom";

export default {
  name: "App",

  components: {
    TopMenu,
    Banner,
    Notice,
    Promo1,
    Promo2,
    Promo3,
    Bottom,
  },

  TopMenudata: () => ({
    //
  }),
};
</script>
<style>
.FloatBanner{
  position:sticky;
  top:150px;
  left:90%;
  width:140px;
  z-index: 100;
}
</style>