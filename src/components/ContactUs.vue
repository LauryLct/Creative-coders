<template>
  <div class="contact-us mt-5" id="4">
    <h2 class='m-5 pt-5'>Nous contacter</h2>
    <div class="phone p-4">
      <img src="../assets/phone.svg" alt="phone-logo">
      <p>Telephone:</p>
      <a class="p-3" href="tel:+33672265043">(+33)672265043</a>
    </div>
    <div class="email p-4">
      <img src="../assets/1.svg" alt="email-logo">
      <p>E-mail:</p>
      <a href="mailto:contact@creative-coders.fr">contact@creative-coders.fr</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ContactUs',
}
</script>

<style scoped>
.contact-us {
  margin: 4rem 0;
}
p {
  margin-bottom: O;
}
img {
  width: 40px;
}
</style>
