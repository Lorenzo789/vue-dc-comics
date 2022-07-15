<template>
  <footer>
    <section class="container">
        <button>Sign Up Now</button>
        <nav>
            <span>Follow Us</span>
            <a href="#"><img src="../assets/img/footer-facebook.png" alt="footer-facebook"></a>
            <a href="#"><img src="../assets/img/footer-periscope.png" alt="footer-periscope"></a>
            <a href="#"><img src="../assets/img/footer-pinterest.png" alt="footer-pinterest"></a>
            <a href="#"><img src="../assets/img/footer-twitter.png" alt="footer-twitter"></a>
            <a href="#"><img src="../assets/img/footer-youtube.png" alt="footer-youtube"></a>
        </nav>
    </section>
  </footer>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import'../styles/variables.scss';
@import'../styles/general.scss';
footer{
    background-color: $footerBg;
    position: relative;
    height: 106px;
    padding: 30px;

    .container{
        width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;

        button{
            padding: 15px;
            background-color: $footerBg;
            border: 2px solid $mainShopBg;
            font-size: 20px;
            color: white;
        }

        span{
            font-size: 30px;
            font-weight: bold;
            color: $mainShopBg;
            vertical-align: super;
            padding: 10px;
        }

        a{
            padding: 10px;
        }
    }
}
</style>