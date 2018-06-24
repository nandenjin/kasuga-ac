<template>
  <main>

    <div class="background"></div>

    <div class="wrapper">
      <section class="eye-catch">
        <div class="copy">
          <img class="copy--0" src="~assets/img/copy--0.svg" alt="自立した">
          <img class="copy--1" src="~assets/img/copy--1.svg" alt="強い">
          <img class="copy--2" src="~assets/img/copy--2.svg" alt="大学へ。">
          <img class="copy--3" src="~assets/img/copy--3.svg" alt="UNIVERSITY OF KASUGA">
        </div>
      </section>

      <section class="section hello">
        <div class="content">
          <img class="logo" src="~assets/img/logo--circle.svg" alt="◎">
          <img class="message" src="~assets/img/message.svg" alt="海原に囲まれた孤島でも。街から離れた孤独の地でも。古来より島国だった日本の民は、もがき、あがき、骨身を尽くして、世界で生き抜く技を手に入れた。いま我々も、同じ心に学び、独り立ちの帆をあげよう。わたしたちは、春日大学">
        </div>
      </section>

      <section class="section intro">
        <div class="content">
          <img class="gakurui" src="~assets/img/gakurui.svg" alt="図書館科学創成学類">
          <img class="thumb" src="~assets/img/photo/library.jpg" alt="">
          <div class="dscr">
            <p>
              図書館科学創成学類では、知識情報学の大元である図書館を中心軸に、最先端の情報技術を駆使した研究を推し進め、コンテンツ・メディアによる新時代の創成を図ります。学類の全体をなす3つの要素を残さずひとところに集めることで、他に頼らない、「自立した大学」としての存在をより一層明らかにします。
            </p>

            <h3>知識情報学</h3>
            <p>「人類の蓄積した知識をいかに武器にできるか」という観点は、学類で行われる学問の中心基軸です。知恵の積み上げをおろそかにせず、着実な歩みによって進化を続ける原動力として、生活への利活用を目指します。</p>

            <h3>情報科学</h3>
            <p>この数十年で目覚ましい発展を遂げてきた情報科学を、万物に対して強力なツールとして利用できるものと捉えます。まさに最新の技術をリアルタイムに取り入れることで、学類自らが最先端の科学を伝え広める場となり、他者を圧する力を高めます。</p>

            <h3>情報メディア</h3>
            <p>基礎的な情報技術の上にコンテンツの流通基盤を作ることで、現代社会により深く浸透したネットワークを理解し、余すところなく活用することのできる人材を育成します。</p>

          </div>
        </div>
      </section>

      <section class="section access">
        <div class="content">
          <img class="title" src="~assets/img/access.svg">
          <photo-stream class="photo-stream"></photo-stream>
          <div class="map-box">
            <img class="map" src="https://maps.googleapis.com/maps/api/staticmap?key=AIzaSyDybnmh8rQphuAAFO7SzROPf8619LUz6YE&center=36.086198,140.106066&zoom=13&format=png&maptype=roadmap&style=element:geometry%7Ccolor:0xf5f5f5&style=element:labels.icon%7Cvisibility:off&style=element:labels.text.fill%7Ccolor:0x616161&style=element:labels.text.stroke%7Ccolor:0xf5f5f5&style=feature:administrative.land_parcel%7Cvisibility:off&style=feature:administrative.land_parcel%7Celement:labels.text.fill%7Ccolor:0xbdbdbd&style=feature:administrative.neighborhood%7Cvisibility:off&style=feature:poi%7Celement:geometry%7Ccolor:0xeeeeee&style=feature:poi%7Celement:labels.text%7Cvisibility:off&style=feature:poi%7Celement:labels.text.fill%7Ccolor:0x757575&style=feature:poi.business%7Cvisibility:off&style=feature:poi.park%7Celement:geometry%7Ccolor:0xe5e5e5&style=feature:poi.park%7Celement:labels.text.fill%7Ccolor:0x9e9e9e&style=feature:road%7Celement:geometry%7Ccolor:0xffffff&style=feature:road%7Celement:labels%7Cvisibility:off&style=feature:road%7Celement:labels.icon%7Cvisibility:off&style=feature:road.arterial%7Celement:labels.text.fill%7Ccolor:0x757575&style=feature:road.highway%7Celement:geometry%7Ccolor:0xdadada&style=feature:road.highway%7Celement:labels.text.fill%7Ccolor:0x616161&style=feature:road.local%7Celement:labels.text.fill%7Ccolor:0x9e9e9e&style=feature:transit%7Cvisibility:off&style=feature:transit.line%7Celement:geometry%7Ccolor:0xe5e5e5&style=feature:transit.station%7Celement:geometry%7Ccolor:0xeeeeee&style=feature:water%7Celement:geometry%7Ccolor:0xc9c9c9&style=feature:water%7Celement:labels.text%7Cvisibility:off&style=feature:water%7Celement:labels.text.fill%7Ccolor:0x9e9e9e&markers=icon:https://www.kasuga-ac.jp/map-pin.png|36.086198,140.106066&size=360x360">
            <div class="text">
              <h3>春日キャンパス</h3>
              <ul>
                <li>つくばエクスプレス線秋葉原駅から快速45分、つくば駅から北へ徒歩10分。</li>
                <li>JR常磐線 ひたち野うしく駅・荒川沖駅・土浦駅からバス・タクシーで各15〜20分。</li>
                <li>常磐自動車道 桜土浦I.C.下車、筑波方面へ向かう。</li>
              </ul>
            </div>
          </div>
        </div>
      </section>

      <section class="section foot">
        <a href="https://www.nandenjin.com/ja/works/kasuga_ac">
          <img src="~assets/img/credit.svg">
        </a>
      </section>

    </div>

  </main>
</template>

<script>

import PhotoStream from '~/components/PhotoStream.vue';

export default {

  components: {

    PhotoStream,

  },

  head() {

    return {

      title: '春日大学 / UNIVERSITY OF KASUGA',
      meta: [
        { name: 'twitter:card', content: 'summary_large_image' },
        { name: 'twitter:creator', content: '@nandenjin' },
        { name: 'twitter:title', content: '春日大学 / UNIVERSITY OF KASUGA' },
        { name: 'twitter:description', content: '自立した強い大学へ。春日キャンパス、図書館科学創成学類を擁する情報系大学。' },
        { name: 'twitter:image', content: 'https://www.kasuga-ac.jp/promo.jpg' },
        { property: 'og:type', content: 'website' },
        { property: 'og:title', content: '春日大学 / UNIVERSITY OF KASUGA' },
        { property: 'og:description', content: '自立した強い大学へ。春日キャンパス、図書館科学創成学類を擁する情報系大学。' },
        { property: 'og:url', content: 'https://www.kasuga-ac.jp' }
      ]

    }

  },

  mounted() {



  }

}

</script>

<style lang="scss">

@import '~assets/scss/global.scss';

html, body{

  width: 100%;
  height: 100%;
  margin: 0;
  overflow-x: hidden;
  background-color: #eee;

}

.background{

  position: fixed;
  top: 0;
  left: 0;
  width: 110vw;
  height: 110vh;

  background: url( '~assets/img/background.png' ) center;
  background-size: cover;

  animation: bg 45s linear 0s infinite;

}

@keyframes bg{

  0%  { transform: translate3d( -10vw, -5vh, 0 ); }
  25% { transform: translate3d( -5vw, -10vh, 0 ); }
  50% { transform: translate3d( 0vw, -5vh, 0 ); }
  75% { transform: translate3d( -5vw, 0vh, 0 ); }
  100%{ transform: translate3d( -10vw, -5vh, 0 ); }

}

.wrapper{

  position: absolute;
  z-index: 50;

}

.eye-catch{

  position: relative;
  width: 100vw;
  height: calc( 100vh - 120px );

  .copy{

    position: absolute;
    top: 0; left: 0; right: 0; bottom: 0;
    width: 700px;
    height: 600px;
    margin: auto;

    @include mq(sp){
      width: 300px;
      height: 300px;
    }

    img{

      display: block;
      width: 600px;
      margin: 30px 0;

      @include mq(sp){

        width: 300px;

      }

    }

  }

}

.section{

  width: 1000px;
  margin: 100px auto;
  border: 1px solid transparent;
  background-color: #fff;


  @include mq(sp){
    width: 100%;
    margin: 50px auto;
  }

  .content{

    margin: 50px 30px;
    border: 1px solid transparent;

    @include mq(sp){
      margin: 25px 15px;
    }

  }

}

.hello{

  text-align: center;

  .logo{

    display: block;
    width: 100px;
    margin: 80px auto;

  }

  .message{

    display: block;
    width: 600px;
    margin: 60px auto 100px auto;

    @include mq(sp){
      width: 300px;
    }

  }

}

.intro{

  .gakurui{

    display: block;
    width: 500px;
    margin: 40px auto;

    @include mq(sp){
      width: 250px;
    }

  }

  .thumb{

    display: block;
    width: 800px;
    margin: 60px auto;

    @include mq(sp){
      width: 300px;
    }

  }

  .dscr{

    max-width: 700px;
    margin: auto;

    font-size: 15px;
    line-height: 25px;

    @include mq(sp){
      max-width: 300px;
    }

  }

}

.access{

  .title{

    display: block;
    width: 500px;
    margin: 50px auto;

    @include mq(sp){
      width: 250px;
    }


  }

  .photo-stream{

    height: 450px;

    @include mq(sp){
      height: 220px;
    }

  }

  .map-box{

    display: flex;

    @include mq(sp){
      display: block;
    }

    .map{

      display: block;
      flex: 0 0 auto;
      margin-right: 30px;

      @include mq(sp){
        margin: 15px auto;
      }

    }

    .text{

      display: block;
      flex: 1 1 auto;
      padding: 20px;
      font-size: 15px;
      line-height: 25px;

    }

  }

}

.foot{

  background-color: #444;
  color: #fff;

  img{
    width: 60%;
    margin: 15px 20%;
  }

}

</style>
