<script>

export default {
    name: 'AppFooter',
    components: {

    }
}
</script>

<template>
    <div class="footer-menu">
        <div class="container wrapper">
            <div class="row">
                <div class="col-2">
                    <ul class="list-unstyled">
                        <h3>DC Comics</h3>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                    <ul class="list-unstyled">
                        <h3>Shop</h3>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>

                    </ul>
                </div>
                <div class="col-2">
                    <ul class="list-unstyled">
                        <h3>DC</h3>
                        <li>Terms of use</li>
                        <li>Privacy Policy(New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificate</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact us</li>


                    </ul>
                </div>
                <div class="col-2">
                    <ul class="list-unstyled">
                        <h3>Sites</h3>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC power Visa</li>
                    </ul>
                </div>
                <div class="logo-bg">
                    <img src="../assets/img/dc-logo-bg.png" alt="">
                </div>
            </div>

        </div>
    </div>
</template>



<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Fira+Sans+Condensed:wght@300;400;500;700&display=swap');

.footer-menu {
    background-image: url('../assets/img/footer-bg.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    padding: 1rem;
}

.wrapper {
    width: 70%;
    margin: auto;
    color: #8b8b8b;
}

.row {
    position: relative;
}

ul h3 {
    color: white;
}

.logo-bg img {
    position: absolute;
    right: 0;
    top: 0;
    width: 340px;

}
</style>