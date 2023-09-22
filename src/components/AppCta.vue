<script>

export default {
    name: 'AppCta',
    components: {

    }
}
</script>

<template>
    <div class="cta d-flex">
        <div class="container d-flex justify-content-between align-items-center flex-wrap">
            <div class="button">
                <button type="button" class="btn cta-btn">
                    <h3>Sign-up now!</h3>
                </button>
            </div>
            <div class="social d-flex gap-3 flex-wrap">
                <div class="follow">
                    <h3>FOLLOW US</h3>
                </div>
                <div class="facebook">
                    <a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a>
                </div>
                <div class="twitter">
                    <a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a>
                </div>
                <div class="youtube">
                    <a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a>
                </div>
                <div class="pinterest">
                    <a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a>
                </div>
                <div class="periscope">
                    <a href="#"> <img src="../assets/img/footer-periscope.png" alt=""></a>
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