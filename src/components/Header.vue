<template>
    <header>
        <div class="container">
            <img src="../assets/img/dc-logo.png" alt="">
            <nav>
                <ul>
                    <li v-for="(link, index) in menuHeaderLinks" :key="index">
                        <a :href="link.url" :class="{'active': index == '1'}">
                            {{ link.text }}
                        </a>
                    </li>
                </ul>
            </nav>
        </div>
        <HeaderContent />
    </header>
</template>

<script>
import HeaderContent from './HeaderContent.vue';
export default {
    components: { HeaderContent },
    data: function(){
        return{
            menuHeaderLinks: [
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
                    text: 'Collectibles',
                    url: '#',
                },
                {
                    text: 'Videos',
                    url: '#',
                },
                {
                    text: 'Fans',
                    url: '#',
                },
                {
                    text: 'News',
                    url: '#',
                },
                {
                    text: 'Shop',
                    url: '#',
                },
            ],
        }
    }
}
</script>

<style lang="scss" scoped>
@import'../styles/variables.scss';
@import'../styles/general.scss';

.container{
    padding: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 1200px;
    margin: 0 auto;
}

.active{
    color: $colorActive;
}

img{
    height: 80px;
}

li{
    display: inline-block;
    padding: 5px 15px;

    a{
        color: black;
        text-decoration: none;
        font-weight: bold;
    }
}


</style>