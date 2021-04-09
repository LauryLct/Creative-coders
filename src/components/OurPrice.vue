<template>
  <div class="our-price" id="3">
    <h2>Nos tarifs</h2>
    <div class="row">
      <div class="col sm-m-5">
        <PriceCard
          title='Site vitrine'
          firstLine="Codage main"
          secondLine="Conception graphique personnalisée"
          thirdLine="Acquisition nom de domaine"
          forthLine="E-mail au nom de l'entreprise"
          fifthLine="Site responsive"
          sixthLine="Mise en ligne du site"
          price="A partir de 1500€"
          />
      </div>
      <div class="col sm-m-5">
        <PriceCard
          title='Site vitrine'
          firstLine="Codage main"
          secondLine="Conception graphique personnalisée"
          thirdLine="Acquisition nom de domaine"
          forthLine="E-mail au nom de l'entreprise"
          fifthLine="Site responsive"
          sixthLine="Mise en ligne du site"
          price="A partir de 1800€"
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
