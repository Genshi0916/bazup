<template>
  <v-app dark>
    <Header></Header>
    <v-main>
      <v-container>
        <nuxt />
      </v-container>
    </v-main>
    <Footer></Footer>
  </v-app>
</template>

<script>
import Header from '../components/Header'
import Footer from '../components/Footer'

export default {
  components:{
    Header,
    Footer
  },

  data () {
    return {
      title: 'BazUp！！'
    }
  }
}
</script>
<style>
  a {
    text-decoration: none;
  }
</style>
