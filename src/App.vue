<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
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
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
