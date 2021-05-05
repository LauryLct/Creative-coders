<template>
    <div class="footer p-5">
        <div class="container">
            <div class="row">
                <div class="col">
                    <h3>A propos</h3>
                    <p>
                        Creative Coders est une entreprise titulaire d'un CAPE jusqu'au 13 avril 2022 maximum - 
                        Espace des Entrepreneurs<br>
                        Siret 418 541 553 000 32<br>
                        Le TVA intracommunautaire FR 23 418 541 553<br>
                        Le code NAF, 8899B
                    </p>
                </div>
                <div class="col">
                    <h3>Contact</h3>
                    <p>Laury Lecaut</p>
                    <a class="p-3" href="tel:+33672265043">(+33)672265043</a>
                    <a href="mailto:laury@creative-coders.fr">laury@creative-coders.fr</a>
                    <p class="pt-1">80, Avenue Roland Moreno. 59410 Anzin</p>
                </div>
                <div class="mt-4 pt-3">
                    <p class="pt-3">Site réalisé par Laury Lecaut - Hébergé chez Netlify</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>


export default {
    name: 'Footer'
}
</script>

<style scoped>
.footer {
    background-color: #3A4750;
    border-top: 5px solid #2185D5;
}

p {
    color: white;
}

a {
    color: white;
}

h3 {
    color: white;
    padding: 30px;
}
</style>