

<!-- Vue e javascript -->
<script>

import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue"
import Main from "./components/Main.vue"
  export default{
    data() {
      return {
        message: "Ciao A Tutti",
      }
    },

    components: {
      Navbar,
      Footer,
      Main,
    }
  }


</script>

<!-- HTML -->
<template>
<div class="container">

  <Navbar></Navbar>
  <Main></Main>
  <Footer></Footer>
  
</div>

</template>

<!-- CSS -->

<style>

.container{
  text-align: center;
  padding-top: 200px;
}





</style>