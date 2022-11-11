<script>
  import Header from "./components/SiteHeader.vue"
  import Main from "./components/SiteMain.vue"
  import Footer from "./components/SiteFooter.vue"
  import Socials from "./components/FooterSocials.vue"
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
