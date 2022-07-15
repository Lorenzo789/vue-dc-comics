<template>
    <main>
        <MainBannerShop />
        <div>
            <ul>
                <h3>DC Comics</h3>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>Tv</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                <h3>Shop</h3>
                <li>Shop DC</li>
                <li>Shop DC Collectibles</li>
            </ul>
            <ul>
                <h3>DC</h3>
                <li>Terms of Use</li>
                <li>Privacy Policy (New)</li>
                <li>Ad Choices</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>Subscriptions</li>
                <li>Talent Workshops</li>
                <li>CPSC Certificates</li>
                <li>Ratings</li>
                <li>Shop Help</li>
                <li>Contact Us</li>
            </ul>
            <ul>
                <h3>Sites</h3>
                <li>DC</li>
                <li>Mad Magazine</li>
                <li>DC Kids</li>
                <li>DC Universe</li>
                <li>DC Power Visa</li>
            </ul>
            <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>
    </main>
</template>

<script>
import MainBannerShop from './MainBannerShop.vue';
export default {
    components: { MainBannerShop }
}
</script>

<style lang="scss" scoped>
div{
    display: flex;
    background-image: url('../assets/img/footer-bg.jpg');
}
</style>