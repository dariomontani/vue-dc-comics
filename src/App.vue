<template>
  <div id="app">
    <Header></Header>
    <Main></Main>
    <FooterUp></FooterUp>
    <Footer></Footer>
    <FooterDown></FooterDown>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import Header from "./components/Header.vue"
import Main from "./components/Main.vue"
import FooterUp from "./components/FooterUp.vue"
import Footer from "./components/Footer.vue"
import FooterDown from "./components/FooterDown.vue"


export default {
  name: "App",
  components: {
    // HelloWorld,
    Header,
    Main,
    FooterUp,
    Footer,
    FooterDown
  },
};
</script>

<style lang="scss">
@import "./assets/scss/style.scss"
</style>
