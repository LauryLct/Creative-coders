<template>
  <div class="contact-us mt-3 mb-3 mb-3 pb-3" id="nous-contacter">
    <h2>Me contacter</h2>
    <div class="phone p-4">
      <img src="../assets/phone.svg" alt="phone-logo">
      <p>Telephone:</p>
      <a class="p-3" href="tel:+33672265043">(+33)672265043</a>
    </div>
    <div class="email p-4">
      <img src="../assets/1.svg" alt="email-logo">
      <p>E-mail:</p>
      <a href="mailto:laury@creative-coders.fr">laury@creative-coders.fr</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ContactUs',
}
</script>

<style scoped>
p {
  margin-bottom: O;
}
img {
  width: 40px;
}
a {
  color: #2185D5;
  text-decoration: none;
}
</style>
