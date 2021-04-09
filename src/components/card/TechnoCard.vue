<template>
  <div class="techno-card row">
    <div class="col">
      <p class="col">{{ technoName }}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TechnoCard',
  props: {
    technoName: String
  }
}
</script>

<style scoped>
.techno-card {
  padding: 10px;
  margin: 30px 25%;
  background-color: #2185D5;
  color: white;
  font-weight: 700;
  border-radius: 10px;
}

.techno-card:hover {
  font-size: 20px;
  transition: 0.3s;
}

p {
  margin-bottom: 0;
}
</style>
