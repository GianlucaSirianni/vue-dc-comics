<template>
    <div class="comicCard">
        <img :src=dettagliProdotto.thumb alt="">
        <p>{{dettagliProdotto.series.toUpperCase()}}</p>
    </div>
</template>

<script>
    export default {
        name: 'ComicComp',
        props: {
            dettagliProdotto: Object
        }
    }

</script>

<style lang="scss" scoped>
.comicCard{
        width: calc(100%/6);
        color: white;
    }
</style>