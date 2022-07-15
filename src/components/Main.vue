<template>
    <main>
        <MainBannerShop />
        <div>
            <ul>
                <h3>DC Comics</h3>
                <li v-for="(comic, index) in comicsDc" :key="index">
                    <a :href="comic.url">
                        {{ comic.text }}
                    </a>
                </li>

                <h3>Shop</h3>
                <li v-for="(shop, index) in shopsDc" :key="index">
                    <a :href="shop.url">
                        {{ shop.text }}
                    </a>
                </li>
            </ul>
            <ul>
                <h3>DC</h3>
                <li v-for="(policy, index) in DcPolicyStuff" :key="index">
                    <a :href="policy.url">
                        {{ policy.text }}
                    </a>
                </li>
            </ul>
            <ul>
                <h3>Sites</h3>
                <li v-for="(site, index) in sitesDc" :key="index">
                    <a :href="site.url">
                        {{ site.text }}
                    </a>
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
                    url: '#',
                },
                {
                    text: 'Comics',
                    url: '#',
                },
                {
                    text: 'Movies',
                    url: '#',
                },
                {
                    text: 'Tv',
                    url: '#',
                },
                {
                    text: 'Games',
                    url: '#',
                },
                {
                    text: 'Videos',
                    url: '#',
                },
                {
                    text: 'News',
                    url: '#',
                },
            ],

            shopsDc: [
                {
                    text: 'Shop DC',
                    url: '#',
                },
                {
                    text: 'Shop DC Collectibles',
                    url: '#',
                },
            ],

            DcPolicyStuff: [
                {
                    text: 'Terms of Use',
                    url: '#',
                },
                {
                    text: 'Privacy Policy (New)',
                    url: '#',
                },
                {
                    text: 'Ad Choices',
                    url: '#',
                },
                {
                    text: 'Advertising',
                    url: '#',
                },
                {
                    text: 'Jobs',
                    url: '#',
                },
                {
                    text: 'Subscriptions',
                    url: '#',
                },
                {
                    text: 'Talent Workshops',
                    url: '#',
                },
                {
                    text: 'CPSC Certificates',
                    url: '#',
                },
                {
                    text: 'Ratings',
                    url: '#',
                },
                {
                    text: 'Shop Help',
                    url: '#',
                },
                {
                    text: 'Contact Us',
                    url: '#',
                },
            ],

            sitesDc: [
                {
                    text: 'DC',
                    url: '#',
                },
                {
                    text: 'Mad Magazine',
                    url: '#',
                },
                {
                    text: 'DC Kids',
                    url: '#',
                },
                {
                    text: 'DC Universe',
                    url: '#',
                },
                {
                    text: 'DC Power Visa',
                    url: '#',
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