<template>
    <div class="jumbotron">

        <div class="header-container">
            <p>current series</p>
        </div>

    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

  @import'../styles/variables.scss';

    .jumbotron{
    background-image: url('../assets/img/jumbotron.jpg');
    height: 400px;
      p{
        background-color: $mainShopBg;
        position: relative;
        width: 20%;
        left: 0;
        top: 370px;
        text-transform: uppercase;
        font-size: 25px;
        font-weight: bold;
        color: white;
        padding: 10px;
      }
    }

    .header-container {
        width: 1200px;
        margin: 0 auto;
    }
</style>