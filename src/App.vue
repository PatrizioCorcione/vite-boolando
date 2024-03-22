<script>
import Header from "../src/components/Header.vue";
import Main from "../src/components/Main.vue";
import Footer from "../src/components/Footer.vue";
// import {Products} from '../src/assets/db.json';

export default{
  components:{
    Header,
    Main,
    Footer,
    // Products,
    
  }
}
</script>

<template>

  

  <Header/>
  <Main/>
  <Footer/>

  
  
</template>

<style lang="scss">

@import './assets/scss/main.scss';

</style>
