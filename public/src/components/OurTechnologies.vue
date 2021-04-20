<template>
  <div class="our-technos mt-5" id="2">
    <h2 class="m-5">Nos technologies</h2>
    <TechnoCard technoName="Html / Css"/>
    <TechnoCard technoName="Javascript"/>
    <TechnoCard technoName="Ruby"/>
    <TechnoCard technoName="PostgreSQL"/>
    <TechnoCard technoName="Ruby On Rails / Vue.js"/>
  </div>
</template>

<script>
import TechnoCard from './card/TechnoCard.vue'
export default {
  name: 'OurTechnos',
  components: {
    TechnoCard
  }
}
</script>

<style scoped>
.our-technos {
  margin-bottom: 80px;
}
</style>
