<template>
  <div class="card price-card m-4">
    <div class="card-body">
      <h3 class="card-title p-3 mb-4">{{ title }}</h3>
      <div class="border-bottom border-secondary pb-4">
        <p class="card-text">{{firstLine}} </p>
        <p class="card-text">{{secondLine}} </p>
        <p class="card-text">{{thirdLine}} </p>
        <p class="card-text">{{forthLine}} </p>
        <p class="card-text">{{fifthLine}} </p>
        <p class="card-text">{{sixthLine}} </p>
        <p class="card-text">{{seventhLine}} </p>

      </div>

      <h2 id="price"> {{price}} </h2>

      <div class="devis">
        <a href="mailto:laury@creative-coders.fr">{{button}}</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TechnoCard',
  props: {
    title: String,
    firstLine: String,
    secondLine: String,
    thirdLine: String,
    forthLine: String,
    fifthLine: String,
    sixthLine: String,
    seventhLine: String,
    price: String,
    button: String,
  }
}
</script>

<style scoped>
.card {
  background-color: #d3e0ea;
}

.devis {
  background-color: #2185D5;
  border-radius: 10px;
  padding: 10px;
  margin: 20px 15%;
}
.devis:hover {
  background-color: #3A4750;
}
a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

h2 {
  font-weight: bold;
}

#price {
  margin: 40px 10px;
}
</style>
