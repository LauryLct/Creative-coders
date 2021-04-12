<template>
    <div class="footer p-5">
        <div class="container">
            <div class="row">
                <div class="col">
                    <h3>A propos</h3>
                    <p>Creative Coders est une entreprise de création de site web sur-mesure. Nous créons des sites à votre image</p>
                </div>
                <div class="col">
                    <h3>Contact</h3>
                    <a class="p-3" href="tel:+33672265043">(+33)672265043</a>
                    <a href="mailto:contact@creative-coders.fr">contact@creative-coders.fr</a>
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