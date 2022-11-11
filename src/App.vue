<script>
  import Header from "./components/Header.vue"
  import Main from "./components/Main.vue"
  import Footer from "./components/Footer.vue"
  import Socials from "./components/Socials.vue"
  import StoreLinks from "./components/StoreLinks.vue"

  export default{
    name: "app",
    components:{
      Header,
      Main,
      Footer,
      Socials,
      StoreLinks,
    },
  }
</script>

<template>
  <Header />
  <Main />
  <StoreLinks />
  <Footer />
  <socials />
</template>

<style lang="scss" scoped>
  
</style>
