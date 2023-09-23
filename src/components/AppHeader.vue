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
        <nav class="navbar d-flex justify-content-between pb-0">

            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <div class="nav-menu">
                <ul class="navbar-nav d-flex flex-row gap-3">
                    <div class="nav-wrap d-flex justify-content-center align-items-center" v-for="item in items">
                        <li class="nav-item">
                            <h6>{{ item.name }}</h6>
                        </li>
                    </div>





                </ul>
            </div>
        </nav>
    </header>
</template>



<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;
@import url('https://fonts.googleapis.com/css2?family=Fira+Sans+Condensed:wght@300;400;500;700&display=swap');

header {
    color: $dc-header-font;
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

.nav-wrap {
    height: 80px;
}

//bordo blu da dare all'item active
// .nav-wrap {
//     border-bottom: 3px solid #0282F9;
// }
</style>