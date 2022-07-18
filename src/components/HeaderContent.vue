<template>
  <div>
    <HeaderContentUp/>

    <HeaderCard/>
  </div>
</template>

<script>
import HeaderContentUp from './HeaderContentUp.vue';
import HeaderCard from './HeaderCard.vue';
export default {
    components: { HeaderContentUp, HeaderCard },
}
</script>

<style lang="scss" scoped>
  @import'../styles/variables.scss';
  @import'../styles/general.scss';

</style>