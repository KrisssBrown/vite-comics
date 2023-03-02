<script >
import HeaderNav from './components/HeaderNav.vue'
import Jumbotron from './components/Jumbotron.vue'
import MerchNav from './components/MerchNav.vue'
import Footer from './components/Footer.vue'
import AboutUs from './components/AboutUs.vue'


export default{
  components:{
    HeaderNav,
    Jumbotron, 
    MerchNav,
    Footer,
    AboutUs
  },


  data(){
    return{

    }
  }
}
</script>



<!-- =============================================== -->

<template>
  <HeaderNav/>
  <Jumbotron/>
  <MerchNav/>
  <Footer/>
  <AboutUs/>
</template>


<!-- =============================================== -->

<style lang="scss" scoped>
#app{
  min-height: 100vh;
}

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
