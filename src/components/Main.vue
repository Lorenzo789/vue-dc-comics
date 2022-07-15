<template>
    <main>
        <MainBannerShop />
        <div>
            <ul>
                <h3>DC Comics</h3>
                <li v-for="(comic, index) in comicsDc" :key="index">
                    {{ comic.text }}
                </li>

                <h3>Shop</h3>
                <li v-for="(shop, index) in shopsDc" :key="index">
                    {{ shop.text }}
                </li>
            </ul>
            <ul>
                <h3>DC</h3>
                <li v-for="(policy, index) in DcPolicyStuff" :key="index">
                    {{ policy.text }}
                </li>
            </ul>
            <ul>
                <h3>Sites</h3>
                <li v-for="(site, index) in sitesDc" :key="index">
                    {{ site.text }}
                </li>
            </ul>
            <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>
    </main>
</template>

<script>
import MainBannerShop from './MainBannerShop.vue';
export default {
    components: { MainBannerShop },

    data: function () {
        return {
            comicsDc: [
                {
                    text: 'Characters',
                },
                {
                    text: 'Comics',
                },
                {
                    text: 'Movies',
                },
                {
                    text: 'Tv',
                },
                {
                    text: 'Games',
                },
                {
                    text: 'Videos',
                },
                {
                    text: 'News',
                },
            ],

            shopsDc: [
                {
                    text: 'Shop DC',
                },
                {
                    text: 'Shop DC Collectibles',
                },
            ],

            DcPolicyStuff: [
                {
                    text: 'Terms of Use',
                },
                {
                    text: 'Privacy Policy (New)',
                },
                {
                    text: 'Ad Choices',
                },
                {
                    text: 'Advertising',
                },
                {
                    text: 'Jobs',
                },
                {
                    text: 'Subscriptions',
                },
                {
                    text: 'Talent Workshops',
                },
                {
                    text: 'CPSC Certificates',
                },
                {
                    text: 'Ratings',
                },
                {
                    text: 'Shop Help',
                },
                {
                    text: 'Contact Us',
                },
            ],

            sitesDc: [
                {
                    text: 'DC',
                },
                {
                    text: 'Mad Magazine',
                },
                {
                    text: 'DC Kids',
                },
                {
                    text: 'DC Universe',
                },
                {
                    text: 'DC Power Visa',
                },
            ],
        }
    }
}
</script>

<style lang="scss" scoped>
div {
    display: flex;
    background-image: url('../assets/img/footer-bg.jpg');
}
</style>