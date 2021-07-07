<template>
  <Navbar/>
  <Header/>
  <div class="container">
    <OurSolutions/>
    <OurEngagements/>
    <WhoWeAre/>
    <OurTechnos/>
    <ContactUs/>
  </div>
  <Footer/>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Header from './components/Header.vue'
import OurSolutions from './components/OurSolutions.vue'
import OurTechnos from './components/OurTechnologies.vue'
import OurEngagements from './components/OurEngagements.vue'
import ContactUs from './components/ContactUs.vue'
import Footer from './components/Footer.vue'
import WhoWeAre from './components/WhoWeAre.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Header,
    OurSolutions,
    OurTechnos,
    OurEngagements,
    WhoWeAre,
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
h2{
  padding: 6rem 0 6rem 0;
  font-size: 40px;
}
.size-content {
  width: -moz-available;
}
</style>
