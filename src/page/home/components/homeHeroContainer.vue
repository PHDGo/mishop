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
</style>
