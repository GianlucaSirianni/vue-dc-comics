<template>
    <div class="gen">
        <nav>
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <div class="navList">
                <div class="listContainer"><a href="#">CHARACTERS</a></div>
                <div class="listContainer"><a href="#">COMICS</a></div>
                <div class="listContainer"><a href="#">MOVIES</a></div>
                <div class="listContainer"><a href="#">TV</a></div>
                <div class="listContainer"><a href="#">GAMES</a></div>
                <div class="listContainer"><a href="#">COLLECTIBLES</a></div>
                <div class="listContainer"><a href="#">VIDEOS</a></div>
                <div class="listContainer"><a href="#">FANS</a></div>
                <div class="listContainer"><a href="#">NEWS</a></div>
                <div class="listContainer"><a href="#">SHOP</a></div>
            </div>
        </nav>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

.gen{
    background-color:white;
    width: 100%;
}
nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 80%;
    margin: auto;
    
}

.navList {
    display: flex;


    div {
        margin: 0 10px;
        height: 100px;
        display: flex;
        align-items: center;
    }

}


a {
    text-decoration: none;
    color: black;


}

.listContainer:hover {
    a{
        color: blue;
    }
        border-bottom: 4px solid blue;
}

img {
    width: 70px;
}
</style>