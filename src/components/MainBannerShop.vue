<template>
    <div>
        <ul>
            <li>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="digital-comics">
                {{ linkDigitalComics }}
            </li>
            <li>
                <img src="../assets/img/buy-comics-merchandise.png" alt="comics-merchandise">
                {{ linkMerchandise }}
            </li>
            <li>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="subscriptions">
                {{ linkSubscription }}
            </li>
            <li>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="shop-locator">
                {{ linkShopLocator }}
            </li>
            <li>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="dc-power-visa">
                {{ linkDcPowerVisa }}
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
        }
    }
}
</script>

<style lang="scss" scoped>

</style>