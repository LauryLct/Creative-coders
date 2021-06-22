<template>

<h2 id="nos-engagements">Mes engagements</h2>

<div class="card-product p-1 mt-4 mb-4">
  <img class="d-none d-lg-block" src="../assets/card/click.svg" />
  <div class="card-product-infos">
    <h2 class='card-title'>Conception web</h2>
    <p>
      Que ce soit un projet de conception de sites vitrines, de sites e-commerces ou d'applications webs, 
      Creative Coders s'adaptera à vos besoins spécifiques. De la création de sites from scratch ou 
      de l'amélioration de votre site actuel, pour connaître nos solutions à vos projets <a href='#nous-contacter'>contactez-nous.</a>
    </p>
  </div>
</div>
<div class="d-flex flex-row-reverse">
  <div class="card-product p-1 m-3">
    <div class="card-product-infos" id="reverse-card">
      <h2 class='card-title'>Nom de domaine et hébergement</h2>
      <p>
        Creative Coders s'occupe des démarches d'acquisition du nom de domaine de votre société.<br/>
        Pour ce qui s'agit de l'hébergement de votre site, Creative Coders s'occupe également d'effectuer toutes les démarches pour vous.
        Dans une optique de toujours respecter votre liberté, la propriété et la gestion de l'hébergement restent toujours sous votre contrôle.

      </p>
    </div>
    <img class="d-none d-lg-block" id="img-reverse" src="../assets/card/www.svg" />
  </div>
</div>
<div class="card-product p-1 m-3">
  <img class="d-none d-lg-block" src="../assets/card/good.svg" />
  <div class="card-product-infos">
    <h2 class='card-title'>Charte graphique</h2>
    <p>
      Une charte graphique personnalisée, correspondant à votre sensibilité et à l'image que vous souhaitez renvoyer de votre entreprise, est réalisée pour chaque projet.
      La proposition de logo et l'établissement d'une maquette en amont du développement de votre site, vous permet de toujours avoir une vision concrète de votre projet 
      et de permettre d'avoir un résultat final au plus proche de vos envies.
    </p>
  </div>
</div>
<div class="d-flex flex-row-reverse">
  <div class="card-product p-1 m-3">
    <div class="card-product-infos" id="reverse-card">
      <h2 class='card-title'>Maintenance et formation</h2>
      <p>
        Creative coders fournit toujours une formation à ses clients une fois le projet terminé, permettant une prise en main rapide.<br/>
        La réalisation de maintenance sur vos sites est également possible, que ce soit sur des projets que nous avons nous-même réalisés, ou sur des projets 
        correspondant à <a href="#nos-technologies">nos téchnologies</a>. Si vous souhaitez connaitre nos tarifs sur une possible maintenance, <a href='#nous-contacter'>contactez-nous.</a>

      </p>
    </div>
    <img class="d-none d-lg-block" id="img-reverse" src="../assets/card/maintenance.svg" />
  </div>
</div>

</template>

<script>
export default {
  name: 'OurTechnos',
}
</script>

<style scoped>

a {
  text-decoration: none;
  color: #4599DE;
}

#img-reverse {
  border: 2px solid #4599DE;
}

#reverse-card {
  flex-grow: 1;
}
.card-product {
  overflow: hidden;
  height: 150px;
  background: white;
  box-shadow: 0 0 15px rgba(0,0,0,0.2);
  display: flex;
  align-items: center;
  width: 80%;
}

.card-product img {
  height: 100%;
  width: 150px;
  object-fit: cover;
  border: 2px solid #3a4750;
  border-radius: 5px;
}

.card-product h2 {
  font-size: 18px;
  font-weight: bold;
  margin: 0;
}

.card-product p {
  font-size: 13px;
  line-height: 1.4;
  opacity: .7;
  margin-bottom: 0;
  margin-top: 8px;
}

.card-product .card-product-infos {
  padding: 16px;
}

.card-title {
  margin: 10px;
  padding: 10px;
}

@media (max-width: 800px) {
  .card-product {
    height: 100%;
  }
} 
</style>

