<template>
  <Navbar/>
  <Header/>
  <div class="container">
    <OurSolutions/>
    <OurTechnos/>
    <OurPrice/>
    <ContactUs/>
  </div>
  <Footer/>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Header from './components/Header.vue'
import OurSolutions from './components/OurSolutions.vue'
import OurTechnos from './components/OurTechnologies.vue'
import OurPrice from './components/OurPrice.vue'
import ContactUs from './components/ContactUs.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Header,
    OurSolutions,
    OurTechnos,
    OurPrice,
    ContactUs,
    Footer
  }
}
</script>

<style>
#app {
  font-family: Quicksand, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  background-color: #F6F5F5;
}
.container {
  text-align: center;
}
h2 {
  padding: 20px;
  margin: 20px;
}
</style>
