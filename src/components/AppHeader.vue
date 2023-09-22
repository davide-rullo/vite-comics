<script>

export default {
    name: 'AppHeader',
    components: {

    }
}
</script>

<template>
    <header>
        <nav class="navbar d-flex justify-content-between">

            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <div class="nav-menu">
                <ul class="navbar-nav d-flex flex-row gap-3">
                    <li class="nav-item">
                        <h6>CHARACTERS</h6>
                    </li>
                    <li class="nav-item">
                        <h6>COMICS</h6>
                    </li>
                    <li class="nav-item">
                        <h6>MOVIES</h6>
                    </li>
                    <li class="nav-item">
                        <h6>TV</h6>
                    </li>
                    <li class="nav-item">
                        <h6>GAMES</h6>
                    </li>
                    <li class="nav-item">
                        <h6>COLLECTIBLES</h6>
                    </li>
                    <li class="nav-item">
                        <h6>VIDEOS</h6>
                    </li>
                    <li class="nav-item">
                        <h6>FANS</h6>
                    </li>
                    <li class="nav-item">
                        <h6>NEWS</h6>
                    </li>
                    <li class="nav-item">
                        <h6>SHOP</h6>
                    </li>




                </ul>
            </div>
        </nav>
    </header>
</template>



<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Fira+Sans+Condensed:wght@300;400;500;700&display=swap');

header {}

body {
    font-family: 'Fira Sans Condensed', sans-serif;

}

.navbar {
    flex-wrap: nowrap;
}

.logo img {
    width: 80px;
}

nav {
    width: 70%;
    margin: auto;
}
</style>