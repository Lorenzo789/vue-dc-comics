<template>
    <div>
        <ul>
            <li>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="digital-comics">
                <a :href="urlLink">
                    {{ linkDigitalComics }}
                </a>
            </li>
            <li>
                <img src="../assets/img/buy-comics-merchandise.png" alt="comics-merchandise">
                <a :href="urlLink">
                    {{ linkMerchandise }}
                </a>
            </li>
            <li>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="subscriptions">
                <a :href="urlLink">
                    {{ linkSubscription }}
                </a>
            </li>
            <li>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="shop-locator">
                <a :href="urlLink">
                    {{ linkShopLocator }}
                </a>
            </li>
            <li>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="dc-power-visa">
                <a :href="urlLink">
                    {{ linkDcPowerVisa }}
                </a>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    data: function(){
        return{
            linkDigitalComics: 'Digital Comics',
            linkMerchandise: 'DC Merchandise',
            linkSubscription: 'Subscription',
            linkShopLocator: 'Comic shop locator',
            linkDcPowerVisa: 'DC Power Visa',
            urlLink: '#',
        }
    }
}
</script>

<style lang="scss" scoped>

</style>