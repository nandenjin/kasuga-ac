
<template>
  
  <header class="site-header">
    <div class="logo">
      <img class="logo--icon" src="~assets/img/logo--icon.svg">
      <span class="logo--separater"></span>
      <img class="logo--text-ja" src="~assets/img/logo--text-ja.svg">
      <img class="logo--text-en" src="~assets/img/logo--text-en.svg">
    </div>
  </header>

</template>

<script>
  
  export default {

  };

</script>

<style lang="scss" scoped>

  @import '~assets/scss/global.scss';

  .site-header{

    width: 100%;
    height: 120px;
    background: #fff;
    box-shadow: 1px 1px 1px 0 rgba( 0, 0, 0, 0.3 );

    @include mq(sp){
      height: 70px;
    }

    .logo{

      height: 100%;
      margin: 0 40px;
      line-height: 120px;

      @include mq(sp){
        margin: 0 20px;
        line-height: 70px;
      }

      img{

        vertical-align: middle;

      }

      .logo--icon{

        height: 70px;
        margin: 0 40px;

        @include mq(sp){
          height: 40px;
          margin: 0 20px;
        }

      }

      .logo--separater{

        display: inline-block;
        width: 2px;
        height: 40px;
        margin-right: 35px;
        background-color: #0ca2e8;
        transform: translateY( 18px );

        @include mq(sp){
          height: 20px;
          transform: translateY(7px);
          margin-right: 17px;
        }

      }

      .logo--text-ja{

        height: 30px;
        margin-right: 30px;

        @include mq(sp){
          height: 15px;
        }

      }

      .logo--text-en{

        height: 30px;

        @include mq(sp){
          display: none;
        }

      }

    }

  }
  

</style>
