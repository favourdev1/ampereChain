<template>
  <NavbarUi></NavbarUi>
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <!-- <div>Hello world</div> -->

  <router-view> </router-view>

  <FooterUi></FooterUi>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import NavbarUi from "./components/common/NavbarUi.vue";
import FooterUi from "./components/common/Footer.vue";
import "./assets/css/style.css";
import  AOS  from "aos";
import "aos/dist/aos.css"
export default {
  name: "App",
  components: {
    NavbarUi,
    FooterUi,
    // HelloWorld
  },
  mounted() {
    AOS.init({
      duration: 400,
    });
    
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Nunito:wght@400;500&display=swap");

#app {
  /* font-family: "Nunito", sans-serif; */
}
body {
  background-color: #000;
}
</style>
