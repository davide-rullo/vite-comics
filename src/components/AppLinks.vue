<script>

export default {
    name: 'AppLinks',
    components: {

    }
}
</script>

<template>
    <div class="links">
        <div class="link-menu d-flex justify-content-center align-items-center gap-5 flex-wrap">
            <div class="link digital d-flex justify-content-center align-items-center">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <p>Digital comics</p>
            </div>
            <div class="link merch d-flex justify-content-center align-items-center">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <p>Merchandise</p>
            </div>
            <div class="link sub d-flex justify-content-center align-items-center">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <p>subscription</p>
            </div>
            <div class="link locator d-flex justify-content-center align-items-center">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <p>Comic shop locator</p>
            </div>
            <div class="link visa d-flex justify-content-center align-items-center">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <p>DC power Visa</p>
            </div>
        </div>
    </div>
</template>



<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Fira+Sans+Condensed:wght@300;400;500;700&display=swap');

.links {

    background-color: #0282F9;
    padding: 1rem 0;


    .link-menu {
        width: 70%;
        padding: 1rem;
        margin: auto;
        color: white;
        text-transform: uppercase;
        gap: 1rem;
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