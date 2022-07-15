<template>
    <div class="banner-shop">
        <div class="container">
            <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="digital-comics">
                <a :href="urlLink">
                    {{ linkDigitalComics }}
                </a>
            </div>
            <div>
                <img src="../assets/img/buy-comics-merchandise.png" alt="comics-merchandise">
                <a :href="urlLink">
                    {{ linkMerchandise }}
                </a>
            </div>
            <div>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="subscriptions">
                <a :href="urlLink">
                    {{ linkSubscription }}
                </a>
            </div>
            <div>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="shop-locator">
                <a :href="urlLink">
                    {{ linkShopLocator }}
                </a>
            </div>
            <div>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="dc-power-visa">
                <a :href="urlLink">
                    {{ linkDcPowerVisa }}
                </a>
            </div>
        </div>
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




@import'../styles/variables.scss';
@import'../styles/general.scss';

.banner-shop {
    padding: 50px;
    background-color: $mainShopBg;
    position: relative;

    .container {
        width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
    
        div {
            display: flex;
            align-items: center;
    
            img {
                height: 50px;
            }
        }
    }

}

a{
    color: white;
    text-decoration: none;
    padding: 5px 10px;
}


</style>