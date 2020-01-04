<template>
  <div class="container">
    
    <Header />
    <!-- <Cards /> -->
    <!-- <Footer /> -->
  </div>
</template>

<script>
import Header from '~/components/Header.vue'
import Footer from '~/components/Footer.vue'
import Cards from '~/components/Cards.vue'
// import Bio from '~/components/Bio.vue'

export default {
  components: {
    Header,
    // Bio,
    Cards,
    Footer
  }
}
</script>

<style>
.container {
  /* background-color: rgb(226, 226, 226); */
  max-width: 100%;
  margin: 0;
}

</style>
