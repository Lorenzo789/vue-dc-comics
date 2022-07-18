<template>
  <div>
    <HeaderContentUp/>

    <div class="header-content">

      <div class="header-container">
        <p>Content goes here</p>
      </div>

    </div>
  </div>
</template>

<script>
import HeaderContentUp from './HeaderContentUp.vue';
export default {
    components: { HeaderContentUp },
}
</script>

<style lang="scss" scoped>
  @import'../styles/variables.scss';
  @import'../styles/general.scss';

  .header-content{
    background-color: $headerBannerBg;
    padding: 50px;
  }

  .header-container{
    width: 1200px;
    margin: 0 auto;
  }

  p{
    font-size: 30px;
    font-weight: bold;
    color: white;
  }
</style>