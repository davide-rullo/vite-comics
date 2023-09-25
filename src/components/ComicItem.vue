<script>
export default {
    name: 'ComicItem',
    props: {
        thumb: String,
        price: String,
        series: String,
        type: String,
    },
    data() {
        return {

        }
    }
}
</script>

<template>
    <div class="col">
        <div class="comics-card">
            <img class="" :src="thumb" alt="">
        </div>
        <p class="img-title">{{ series }} </p>


    </div>
</template>


<style lang="scss" scoped>
.comics-card img {
    width: 100%;
    aspect-ratio: 1/1;
}

.img-title {
    text-transform: uppercase;
}
</style>