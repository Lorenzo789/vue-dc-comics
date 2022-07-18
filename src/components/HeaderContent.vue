<template>
  <div class="header-content">
    <div>
      <p>Content goes here</p>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  @import'../styles/variables.scss';
  @import'../styles/general.scss';

  .header-content{
    background-color: $headerBannerBg;
    padding: 50px;
  }

.header-content>div{
  width: 1200px;
  margin: 0 auto;
}

  p{
    font-size: 30px;
    font-weight: bold;
    color: white;
  }
</style>