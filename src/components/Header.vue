<template>
    <header>
        <div>
            <img src="../assets/img/dc-logo.png" alt="">
            <nav>
                <ul>
                    <li v-for="(link, index) in menuHeaderLinks" :key="index">
                        <a :href="link.url">
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