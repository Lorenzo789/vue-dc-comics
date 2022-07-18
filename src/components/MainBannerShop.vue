<template>
    <div class="banner-shop">
        <div class="container">
            <div v-for="(link, index) in shopLinks" :key="index">
                <img :src="require(`../assets/img/buy-${link.url}`)" :alt="link.text">
                <a href="#">
                    {{ link.text }}
                </a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data: function(){
        return{
            shopLinks: [
                {
                    text: 'Digital Comics',
                    url: 'comics-digital-comics.png'
                },
                {
                    text: 'DC Merchandise',
                    url: 'comics-merchandise.png',
                },
                {
                    text: 'Subscription',
                    url: 'comics-subscriptions.png',
                },
                {
                    text: 'Comic shop locator',
                    url: 'comics-shop-locator.png',
                },
                {
                    text: 'DC Power Visa',
                    url: 'dc-power-visa.svg',
                },
            ]
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