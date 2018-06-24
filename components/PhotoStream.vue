
<template>
  
  <div class="photo-stream">
    <img :class="{ 'left': step >= 1 }" src="~assets/img/photo/campus_0.jpg" alt="">
    <img :class="{ 'left': step >= 2, 'right': step < 1 }" src="~assets/img/photo/campus_1.jpg" alt="">
    <img :class="{ 'left': step >= 3, 'right': step < 2 }" src="~assets/img/photo/campus_2.jpg" alt="">
    <img :class="{ 'left': step >= 4, 'right': step < 3 }" src="~assets/img/photo/campus_3.jpg" alt="">
    <img :class="{ 'right': step < 4 }" src="~assets/img/photo/campus_4.jpg" alt="">
  </div>

</template>

<script>
  
  export default {

    data() {

      return {

        step: 0,
        direction: 0,

      }

    }, 

    mounted() {

      setInterval( () => {

        if( this.direction === 0 ){

          this.step++;
          if( this.step === 4 ) this.direction = 1;

        }else{

          this.step--;
          if( this.step === 0 ) this.direction = 0;

        }

      }, 5000 );

    }

  };

</script>

<style lang="scss" scoped>

  .photo-stream{

    position: relative;
    width: 100%;
    margin: 40px 0;
    overflow: hidden;

    img{

      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;

      transition: left 0.3s ease-out 0s;

      &.left{ left: -100%; }
      &.right{ left: 100%; }

    }

  }

</style>
