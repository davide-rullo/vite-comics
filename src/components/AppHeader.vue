<script>

export default {
    name: 'AppHeader',
    data() {
        return {
            items: [
                {
                    name: 'Characters'
                },
                {
                    name: 'Comics'
                },
                {
                    name: 'Movies'
                },
                {
                    name: 'TV'
                },
                {
                    name: 'Games'
                },
                {
                    name: 'Collectibles'
                },
                {
                    name: 'Videos'
                },
                {
                    name: 'Fans'
                },
                {
                    name: 'News'
                },
                {
                    name: 'Shop'
                },
            ]
        }
    },
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

                    <li class="nav-item" v-for="item in items">
                        <h6>{{ item.name }}</h6>
                    </li>





                </ul>
            </div>
        </nav>
    </header>
</template>



<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Fira+Sans+Condensed:wght@300;400;500;700&display=swap');

header {
    color: #464646;
}

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

.nav-item {
    text-transform: uppercase;
}
</style>