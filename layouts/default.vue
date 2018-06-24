
<template>
  
  <div>
    <site-header class="site-header"></site-header>
    <nuxt class="content"></nuxt>
    <site-footer></site-footer>
  </div>

</template>

<script>

  import SiteHeader from '~/components/SiteHeader.vue';
  import SiteFooter from '~/components/SiteFooter.vue';
  
  export default {

    components: {

      SiteHeader,
      SiteFooter

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
    z-index: 50;

  }

</style>
