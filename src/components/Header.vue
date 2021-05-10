<template>
  <div class="header">
    <h1 id="first-title">Creative</h1>
    <h1 id="second-title">coders</h1>
    <p id="subtitle">Créateur de solutions web</p>

    <a href="#nos-solutions">
      <div class="arrow-link">
        <img src="../assets/arrow.svg" alt="arrow-logo">
      </div>
    </a>
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
  color: #3A4750;
  font-size: 10vh;
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
  font-size: 7vh;
  padding-top: 5%;
  color: #3A4750;
}

.header {
  position: relative;
  width: 100%;
  height: 100vh;
  background-image: url('../assets/header.jpg');
  -webkit-background-size: cover;
}

.arrow-link{
  position: absolute;
  text-align: center;
  bottom: 10%;
  left: 50%;
  background-color: #f3f3f3;
  padding: 20px 20px;
  border-radius: 20px;
}
.arrow-link:hover{
  background-color: #2185d5;
}
img {
  width: 40px;
}
@media (max-width: 767px) {
  #first-title{
    padding-top: 30%;
  }
  h1 {
    font-size: 8vh;
  }
  #subtitle {
    font-size: 5vh;
  }
  .arrow-link {
    display: none;
  }
}
</style>
