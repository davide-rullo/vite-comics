<script>

export default {
    name: 'AppLinks',
    components: {

    }
}
</script>

<template>
    <div class="links">
        <div class="container">
            <div class="row justify-content-center align-items-center">
                <div class="col-12 col-md-4 col-lg-2">
                    <div class="link-menu d-flex">
                        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                        <p>Digital comics</p>

                    </div>
                </div>
                <div class="col-12 col-md-4 col-lg-2">
                    <div class="link-menu d-flex">
                        <img src="../assets/img/buy-comics-merchandise.png" alt="">
                        <p>Merchandise</p>
                    </div>
                </div>
                <div class="col-12 col-md-4 col-lg-2">
                    <div class="link-menu d-flex">
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                        <p>subscription</p>
                    </div>
                </div>
                <div class="col-12 col-md-4 col-lg-2">
                    <div class="link-menu d-flex">
                        <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                        <p>Comic shop locator</p>
                    </div>
                </div>
                <div class="col-12 col-md-4 col-lg-2">
                    <div class="link-menu d-flex">
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                        <p>DC power Visa</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>



<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;
@import url('https://fonts.googleapis.com/css2?family=Fira+Sans+Condensed:wght@300;400;500;700&display=swap');

.links {

    background-color: $dc-primary;
    padding: 1rem 0;


    .link-menu {
        width: 70%;
        padding: 1rem;
        margin: auto;
        color: $dc-white;
        text-transform: uppercase;
        gap: 1rem;
        justify-content: center;
        align-items: center;
    }

    .link {
        gap: 1rem;
    }

    img {
        max-width: 70px;
        max-height: 70px;
    }
}
</style>