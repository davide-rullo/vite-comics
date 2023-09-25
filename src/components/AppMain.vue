<script>

import comics from "../comics";
import ComicItem from "./ComicItem.vue";





export default {
    name: 'AppMain',
    data() {
        return {
            comics: comics
        };
    },
    components: { ComicItem }
}
</script>

<template>
    <main>
        <div class="content d-flex align-items-center">
            <div class="container">
                <div class="row row-cols-1 row-cols-sm-3 row-cols-md-4 row-cols-lg-6">
                    <ComicItem :thumb="comic.thumb" :series="comic.series" :type="comic.type" :price="comic.price"
                        v-for="comic in comics" />


                </div>
            </div>
        </div>
    </main>
</template>



<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Fira+Sans+Condensed:wght@300;400;500;700&display=swap');

main {
    background-color: #1C1C1C;
}

.container {
    padding: 2.5rem 1rem;
}

.content {
    width: 70%;
    margin: auto;

    color: white;

}
</style>