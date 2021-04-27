<template>
  <div class="our-price mt-3" id="3">
    <h2>Nos tarifs</h2>
    <div class="row">
      <div class="col sm-m-5">
        <PriceCard
          title='Site vitrine'
          firstLine="Codage main"
          secondLine="Conception graphique personnalisée"
          thirdLine="Proposition de logo"
          forthLine="Acquisition nom de domaine"
          fifthLine="E-mail d'entreprise personnalisé"
          sixthLine="Site responsive"
          seventhLine="Mise en ligne du site"
          price="À partir de 1500€ TTC"
          button='Demande de devis'
          />
      </div>
      <div class="col sm-m-5">
        <PriceCard
          title='Site e-commerce'
          firstLine="Codage main"
          secondLine="Conception graphique personnalisée"
          thirdLine="Proposition de logo"
          forthLine="Acquisition nom de domaine"
          fifthLine="E-mail d'entreprise personnalisé"
          sixthLine="Site responsive"
          seventhLine="Mise en ligne du site"
          price="À partir de 1800€ TTC"
          button='Demande de devis'
          />
      </div>
      <div class="col sm-m-5">
        <PriceCard
          title='Développement personnalisé ou maintenance'
          price="Tarif journalier de 350€/jour"
          button='Nous contacter'
          />
      </div>
    </div>
  </div>
</template>

<script>
import PriceCard from './card/PriceCard.vue'
export default {
  name: 'OurTechnos',
  components: {
    PriceCard
  }
}
</script>

<style scoped>
h2 {
  padding-top: 6rem;
}
</style>
