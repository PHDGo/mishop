<template>
  <div class="site-header">
    <swiper :options="swiperOptions">
      <swiper-slide>
        <a target="_blank" href="">
          <img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/755aca9487082e7698e16f17cfb70839.jpg?thumb=1&w=1533&h=575" alt="">
        </a>
      </swiper-slide>
      <swiper-slide>
        <a target="_blank" href="">
          <img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/9976e4391e32311c9e0afad48f943903.jpg?w=2452&h=920" alt="">
        </a>
      </swiper-slide>
      <swiper-slide>
        <a target="_blank" href="">
          <img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/d4174e5766a6e995c66d671615286c84.jpg?thumb=1&w=1533&h=575" alt="">
        </a>
      </swiper-slide>
      <swiper-slide>
        <a target="_blank" href="">
          <img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/172b10e8dbf217313cfb73b5cb51e853.jpg?thumb=1&w=1533&h=575" alt="">
        </a>
      </swiper-slide>
      <swiper-slide>
        <a target="_blank" href="">
          <img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/6bd4174b8c5aad67a64864a5716ad152.jpg?thumb=1&w=1533&h=575" alt="">
        </a>
      </swiper-slide>
      <div class="swiper-pagination"  slot="pagination"></div>
      <div class="swiper-button-prev" slot="button-prev"></div>
      <div class="swiper-button-next" slot="button-next"></div>
    </swiper>
    <div class="home-hero-sub clearfix">
      <div class="span4">
        <ul class="home-channel-list clearfix">
          <li>
            <a href="">
              <img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/82abdba456e8caaea5848a0cddce03db.png?w=48&h=48" alt="">
              小米秒杀
            </a>
          </li>
          <li>
            <a href="">
              <img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/806f2dfb2d27978e33fe3815d3851fa3.png?w=48&h=48" alt="">
              企业团购
            </a>
          </li>
          <li>
            <a href="">
              <img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/eded6fa3b897a058163e2485532c4f10.png?w=48&h=48" alt="">
              F码通道
            </a>
          </li>
          <li>
            <a href="">
              <img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/43a3195efa6a3cc7662efed8e7abe8bf.png?w=48&h=48" alt="">
              米粉卡
            </a>
          </li>
          <li>
            <a href="">
              <img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/f4846bca6010a0deb9f85464409862af.png?w=48&h=48" alt="">
              以旧换新
            </a>
          </li>
          <li>
            <a href="">
              <img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/9a76d7636b08e0988efb4fc384ae497b.png?w=48&h=48" alt="">
              话费充值
            </a>
          </li>
        </ul>
      </div>
      <ul class="home-promo-list">
        <li class="first">
          <a href="">
            <img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/7bc54a61b927dd8c54ddd39a0acf0254.jpg?w=632&h=340" alt="">
          </a>
        </li>
        <li>
          <a href="">
            <img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/94c74e01afe50a86c3a87ff030b85781.jpg?w=632&h=340" alt="">
          </a>
        </li>
        <li>
          <a href="">
            <img src="https://cdn.cnbj1.fds.api.mi-img.com/mi-mall/816a66edef10673b4768128b41804cae.jpg?w=632&h=340" alt="">
          </a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeroContainer',
  data () {
    return {
      swiperOptions: {
        pagination: {
          el: '.swiper-pagination',
          clickable: true
        },
        navigation: {
          nextEl: '.swiper-button-next',
          prevEl: '.swiper-button-prev'
        },
        effect: 'fade',
        speed: 800,
        noSwiping: true,
        autoplay: true,
        loop: true
      }
    }
  }
}
</script>

<style scoped>
.site-header {
  width: 1226px;
  margin: 0 auto 26px;
}

.swiper-container {
  height: 460px;
}

.swiper-slide {
  height: 460px;
}

.swiper-slide img {
  width: 1226px;
  height: 460px;
}

.swiper-pagination {
  position: absolute;
  width: 440px;
  left: auto;
  right: 30px;
  bottom: 20px;
  text-align: right;
}

.swiper-pagination >>> .swiper-pagination-bullet {
  width: 6px;
  height: 6px;
  border: 2px solid #fff;
  background: rgba(0,0,0,.4);
}

.swiper-pagination >>> .swiper-pagination-bullet:hover {
  background: hsla(0,0%,100%,.4);
  border-color: rgba(0,0,0,.4);
}

.swiper-pagination >>> .swiper-pagination-bullet-active {
  background: hsla(0,0%,100%,.4);
  border-color: rgba(0,0,0,.4);
}

.swiper-button-prev,
.swiper-button-next {
  top: 50%;
  width: 41px;
  height: 69px;
  margin-top: -35px;
}

.swiper-button-prev::after,
.swiper-button-next::after {
  content: "";
}

.swiper-button-prev {
  left: 234px;
  background: url(//i1.mifile.cn/f/i/2014/cn/icon/icon-slides.png) no-repeat -84px 50%;
}

.swiper-button-next {
  right: 0px;
  background: url(//i1.mifile.cn/f/i/2014/cn/icon/icon-slides.png) no-repeat -125px 50%;
}

.swiper-button-prev:hover {
  background-position: 0px 50%;
}

.swiper-button-next:hover {
  background-position: -42px 50%;
}

.home-hero-sub {
  width: 1226px;
  margin-top: 14px;
}

.home-hero-sub .span4 {
  float: left;
}

.home-hero-sub .home-channel-list {
  width: 228px;
  padding: 3px;
  background: #5f5750;
  font-size: 12px;
  text-align: center;
}

.home-hero-sub .home-channel-list li,
.home-hero-sub .home-promo-list li {
  float: left;
}

.home-hero-sub .home-channel-list li {
  position: relative;
  width: 70px;
  height: 82px;
  padding: 0 3px;
}

.home-hero-sub .home-channel-list li::before,
.home-hero-sub .home-channel-list li::after {
  content: "";
  position: absolute;
  background: #665e57;
}

.home-hero-sub .home-channel-list li::before {
  top: -1px;
  left: 6px;
  width: 64px;
  height: 1px;
}

.home-hero-sub .home-channel-list li::after {
  top: 6px;
  left: 1px;
  width: 1px;
  height: 70px;
}

.home-hero-sub .home-channel-list a {
  display: block;
  padding-top: 18px;
  color: #fff;
  opacity: .7;
  transition: opacity .2s;
}

.home-hero-sub .home-channel-list a:hover {
  opacity: 1;
}

.home-hero-sub .home-channel-list img {
  display: block;
  width: 24px;
  height: 24px;
  margin: 0 auto 4px;
}

.home-hero-sub .home-promo-list {
  float: left;
  margin-left: 14px;
}

.home-hero-sub .home-promo-list li {
  width: 316px;
  height: 170px;
  margin-left: 15px;
  transition: box-shadow .2s linear;
}

.home-hero-sub .home-promo-list li:hover {
  box-shadow: 0 15px 30px rgba(0,0,0,.1);
}

.home-hero-sub .home-promo-list li.first {
  margin-left: 0;
}

.home-hero-sub .home-promo-list a {
  display: block;
  height: 170px;
  background: url(//i1.mifile.cn/f/i/2014/cn/placeholder-80.png) no-repeat 50%;
}

.home-hero-sub .home-promo-list img {
  width: 316px;
  height: 170px;
}
</style>
