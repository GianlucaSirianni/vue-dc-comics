<template>
    <div class="gen">
        <div class="jumbotron">
            <div class="currentSeries">
                <p>CURRENT SERIES</p>
            </div>
        </div>

    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

    .gen{
        width: 100%;
        
    }
    .jumbotron{
        width: 100vw;
        height: 300px;
        background-image: url(../assets/img/jumbotron.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        position: relative;
    }

    .currentSeries{
        width: 200px;
        height: 50px;
        background-color: blue;
        display: flex;
        align-items: center;
        justify-content: center;
        color: white;
        position: absolute;
        bottom: -25px;
        left: 125px;
    }
</style>