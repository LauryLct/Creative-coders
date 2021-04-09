<template>
  <div class="header">
    <h1 id="first-title">Creative</h1>
    <h1 id="second-title">coders</h1>
    <p id="subtitle">Créateur de solutions web</p>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-weight: bold;
  color: #276678;
  font-size: 7vh;
}
#first-title {
  padding-top: 10%;
  padding-left: 10%;
}
#second-title {
  padding-left: 20%;
}
#subtitle {
  padding-left: 10%;
  font-size: 40px;
  padding-top: 5%;
  color: #276678;
}

.header {
  width: 100%;
  height: 90vh;
  background-image: url('../assets/header.jpg');
  -webkit-background-size: cover;
}
</style>
