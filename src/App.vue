<template>
  <v-app>
    <v-main>
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