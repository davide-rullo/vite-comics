<script>

export default {
    name: 'AppCta',
    components: {

    }
}
</script>

<template>
    <div class="cta d-flex">
        <div class="container d-flex justify-content-between align-items-center">
            <div class="button">
                <button type="button" class="btn cta-btn">
                    <h3>Sign-up now!</h3>
                </button>
            </div>
            <div class="social d-flex gap-3">
                <div class="follow">
                    <h3>FOLLOW US</h3>
                </div>
                <div class="facebook">
                    <img src="../assets/img/footer-facebook.png" alt="">
                </div>
                <div class="twitter">
                    <img src="../assets/img/footer-twitter.png" alt="">
                </div>
                <div class="youtube">
                    <img src="../assets/img/footer-youtube.png" alt="">
                </div>
                <div class="pinterest">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                </div>
                <div class="periscope">
                    <img src="../assets/img/footer-periscope.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>



<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Fira+Sans+Condensed:wght@300;400;500;700&display=swap');

.cta {
    background-color: #303030;
    padding: 2rem;
}

.cta-btn {
    border: 1px solid #0282F9;
    color: white;
}

.follow {
    color: #0282F9;
}
</style>