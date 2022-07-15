<template>
  <section id="app">
    <Header/>
    <Main/>
    <Footer/>
  </section>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style lang="scss">
  @import'./styles/variables.scss';
  @import'./styles/general.scss';

  #app{
    font-family: 'Roboto', sans-serif;
  };
</style>
