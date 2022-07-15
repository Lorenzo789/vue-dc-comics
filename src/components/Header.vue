<template>
    <header>
        <div>
            <img src="../assets/img/dc-logo.png" alt="">
            <nav>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>Tv</li>
                    <li>Games</li>
                    <li>Collectibles</li>
                    <li>Videos</li>
                    <li>Fans</li>
                    <li>News</li>
                    <li>Shop</li>
                </ul>
            </nav>
        </div>
        <HeaderContent />
    </header>
</template>

<script>
import HeaderContent from './HeaderContent.vue';
export default {
    components: { HeaderContent }
}
</script>

<style lang="scss" scoped>
div{
    display: flex;
    justify-content: space-around;
    align-items: center;
}
li{
    display: inline-block;
    padding: 5px;
}


</style>