
<template>
  
  <div>
    <site-header class="site-header"></site-header>
    <nuxt class="content"></nuxt>
  </div>

</template>

<script>

  import SiteHeader from '~/components/SiteHeader.vue';
  
  export default {

    components: {

      SiteHeader,

    }

  };

</script>

<style lang="scss" scoped>
  
  .site-header{
    
    position: fixed;
    top: 0;
    left: 0;
    z-index: 100;

  }

  .content{

    position: absolute;
    top: 120px;

  }

</style>
