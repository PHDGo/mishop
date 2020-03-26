<template>
  <div class="header">
    <div class="site-topbar">
      <div class="container clearfix">
        <div class="topbar-nav">
          <a href="">小米商城</a>
          <span class="sep">|</span>
          <a href="">MIUI</a>
          <span class="sep">|</span>
          <a href="">loT</a>
          <span class="sep">|</span>
          <a href="">云服务</a>
          <span class="sep">|</span>
          <a href="">金融</a>
          <span class="sep">|</span>
          <a href="">有品</a>
          <span class="sep">|</span>
          <a href="">小爱开放平台</a>
          <span class="sep">|</span>
          <a href="">企业团购</a>
          <span class="sep">|</span>
          <a href="">资质证照</a>
          <span class="sep">|</span>
          <a href="">协议规则</a>
          <span class="sep">|</span>
          <a class="topbar-download" href="">
            下载app
            <span class="appcode">
              <img src="https://i1.mifile.cn/f/i/17/appdownload/download.png?1" alt="" width="90px" height="90px">
              小米商城APP
            </span>
          </a>
          <span class="sep">|</span>
          <a href="">Select Location</a>
        </div>
        <div class="topbar-cart">
          <a href="" class="cart-mini">
            <span class="iconfont icon-cart-Empty"></span>
            购物车
            <span>(0)</span>
          </a>
        </div>
        <div class="topbar-info">
          <a class="link" href="">登录</a>
          <span class="sep">|</span>
          <a class="link" href="">注册</a>
          <span class="sep">|</span>
          <span class="message">
            <a href="">消息通知</a>
          </span>
        </div>
      </div>
    </div>
    <div class="site-header">
      <div class="header-logo">
        <a class="logo" href=""></a>
      </div>
      <div class="header-nav">
        <ul class="nav-list clearfix">
          <li class="nav-category">
            <span class="text">全部商品分类</span>
            <div class="site-category">
              <ul class="site-category-list clearfix">
                <li class="category-item">
                  <a href="" class="title">
                    手机 电话卡
                    <span class="iconfont icon-previewright"></span>
                  </a>
                </li>
                <li class="category-item">
                  <a href="" class="title">
                    电视 盒子
                    <span class="iconfont icon-previewright"></span>
                  </a>
                </li>
                <li class="category-item">
                  <a href="" class="title">
                    笔记本 显示器 平板
                    <span class="iconfont icon-previewright"></span>
                  </a>
                </li>
                <li class="category-item">
                  <a href="" class="title">
                    家电 插线板
                    <span class="iconfont icon-previewright"></span>
                  </a>
                </li>
                <li class="category-item">
                  <a href="" class="title">
                    出行 穿戴
                    <span class="iconfont icon-previewright"></span>
                  </a>
                </li>
                <li class="category-item">
                  <a href="" class="title">
                    智能 路由器
                    <span class="iconfont icon-previewright"></span>
                  </a>
                </li>
                <li class="category-item">
                  <a href="" class="title">
                    电源 配件
                    <span class="iconfont icon-previewright"></span>
                  </a>
                </li>
                <li class="category-item">
                  <a href="" class="title">
                    健康 儿童
                    <span class="iconfont icon-previewright"></span>
                  </a>
                </li>
                <li class="category-item">
                  <a href="" class="title">
                    耳机 音箱
                    <span class="iconfont icon-previewright"></span>
                  </a>
                </li>
                <li class="category-item">
                  <a href="" class="title">
                    生活 箱包
                    <span class="iconfont icon-previewright"></span>
                  </a>
                </li>
              </ul>
            </div>
          </li>
          <li class="nav-item">
            <a href="" class="link">小米手机</a>
            <div class="item-children"></div>
          </li>
          <li class="nav-item">
            <a href="" class="link">Redmi 红米</a>
            <div class="item-children"></div>
          </li>
          <li class="nav-item">
            <a href="" class="link">电视</a>
            <div class="item-children"></div>
          </li>
          <li class="nav-item">
            <a href="" class="link">笔记本</a>
            <div class="item-children"></div>
          </li>
          <li class="nav-item">
            <a href="" class="link">家电</a>
            <div class="item-children"></div>
          </li>
          <li class="nav-item">
            <a href="" class="link">路由器</a>
            <div class="item-children"></div>
          </li>
          <li class="nav-item">
            <a href="" class="link">智能硬件</a>
            <div class="item-children"></div>
          </li>
          <li class="nav-item">
            <a href="" class="link">服务</a>
            <div class="item-children"></div>
          </li>
          <li class="nav-item">
            <a href="" class="link">社区</a>
            <div class="item-children"></div>
          </li>
        </ul>
      </div>
      <div class="header-search">
        <form class="search-form" action="//search.mi.com/search" method="get">
          <input type="text" class="search-text">
          <input type="submit" class="iconfont icon-sousuo search-btn" value="">
          <div class="search-hot-words">
            <a href="https://www.mi.com/mi9pro/">小米9 Pro 5G</a>
            <a href="https://www.mi.com/redminote8">Redmi Note 8</a>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style scoped>
.site-topbar a {
  display: inline-block;
  color: #b0b0b0;
}

.site-topbar a:hover {
  color: #fff;
}

.site-topbar {
  height: 40px;
  font-size: 12px;
  color: #b0b0b0;
  background: #333;
}

.site-topbar .container {
  width: 1226px;
  margin: 0 auto;
}

.topbar-nav {
  float: left;
  height: 40px;
  line-height: 40px;
}

.topbar-nav .topbar-download {
  position: relative;
}

.topbar-nav .topbar-download:hover::before {
  content: "";
  position: absolute;
  bottom: 0px;
  left: 50%;
  width: 0px;
  height: 0px;
  margin-left: -8px;
  border-width: 0 8px 8px;
  border-style: solid;
  border-color: transparent transparent #fff;
}

.topbar-nav .appcode {
  position: absolute;
  top: 40px;
  left: 50%;
  width: 124px;
  height: 0px;
  margin-left: -55px;
  box-shadow: 0 3px 5px #aaa;
  background: #fff;
  text-align: center;
  font-size: 14px;
  color: #333;
  line-height: 1;
  overflow: hidden;
  transition: height .3s;
}

.topbar-nav .topbar-download:hover .appcode{
  height: 148px;
}

.topbar-nav .appcode img {
  display: block;
  margin: 18px auto 12px;
}

.topbar-nav .sep {
  margin: 0 .3em;
  font-family: sans-serif;
  color: #424242;
}

.topbar-cart,
.topbar-info {
  float: right;
  height: 40px;
  line-height: 40px;
}

.topbar-cart {
  width: 120px;
  margin-left: 15px;
}

.topbar-cart .icon-cart-Empty {
  margin-right: 4px;
  vertical-align: -3px;
  font-size: 20px;
}

.topbar-info {
  float: right;
}

.topbar-info .sep {
  color: #424242;
}

.topbar-info .link {
  padding: 0 5px;
}

.topbar-info .message {
  padding: 0 10px;
}

.site-topbar .cart-mini {
  display: block;
  height: 40px;
  background: #424242;
  text-align: center;
}

.site-header {
  width: 1226px;
  height: 100px;
  margin: 0 auto;
}

.site-header .header-logo {
  float: left;
  width: 62px;
  margin-top: 22px;
  overflow: hidden;
}

.site-header .logo {
  position: relative;
  display: block;
  width: 55px;
  height: 55px;
  background-color: #ff6700;
}

.site-header .logo::before,
.site-header .logo::after {
  content: "";
  position: absolute;
  top: 0px;
  left: 0px;
  width: 55px;
  height: 55px;
  transition: all .2s;
}

.site-header .logo::before {
  background: url('https://s02.mifile.cn/assets/static/image/mi-logo.png') no-repeat 50% 50%;
  opacity: 1;
}

.site-header .logo::after {
  margin-left: -55px;
  background: url('//s02.mifile.cn/assets/static/image/mi-home.png') no-repeat 50% 50%;
  opacity: 0;
}

.site-header .header-nav {
  float: left;
  width: 850px;
}

.site-header .logo:hover::after,
.site-header .logo:hover::before {
  transform: translateX(55px);
}

.site-header .logo:hover::after {
  opacity: 1;
}

.site-header .logo:hover::before {
  opacity: 0;
}

.header-nav .nav-list {
  /* width: 1100px; */
  height: 88px;
  padding: 12px 0 0 30px;
}

.header-nav .nav-category {
  position: relative;
  float: left;
  width: 127px;
  padding-right: 15px;
}

.header-nav .text {
  display: block;
  visibility: hidden;
  padding: 26px 0 38px;
  text-align: right;
}

.header-nav .site-category {
  position: absolute;
  top: 88px;
  left: -92px;
  width: 234px;
  height: 460px;
  font-size: 14px;
  z-index: 2;
}

.site-category .title {
  display: block;
  position: relative;
  height: 42px;
  padding-left: 30px;
  line-height: 42px;
  color: #fff;
}

.site-category .title span {
  position: absolute;
  top: 12px;
  right: 18px;
  font-size: 18px;
  line-height: 16px;
  color: #e0e0e0;
}

.header-nav .site-category-list {
  height: 420px;
  padding: 20px 0;
  background: rgba(105,101,101,.6)
}

.header-nav .nav-item {
  float: left;
  font-size: 16px;
}

.header-nav .link {
  display: block;
  padding: 26px 10px 38px;
  color: #333;
}

.site-header .header-search {
  float: right;
  width: 296px;
  margin-top: 25px;
}

.site-header .search-form {
  position: relative;
  width: 296px;
  height: 50px;
}

.site-header .search-text,
.site-header .search-btn {
  position: absolute;
  top: 0;
  border: 1px solid #e0e0e0;
  outline: 0;
}

.site-header .search-text {
  display: block;
  right: 51px;
  width: 223px;
  height: 48px;
  padding: 0 10px;
}

.site-header .search-btn {
  right: 0;
  width: 52px;
  height: 50px;
  background: #fff;
  font-size: 24px;
  line-height: 24px;
  color: #616161;
}

.site-header .search-hot-words {
  position: absolute;
  top: 14px;
  right: 62px;
}

.site-header .search-hot-words a {
  display: inline-block;
  padding: 0 5px;
  margin-left: 5px;
  background: #eee;
  font-size: 12px;
  color: #757575;
  transition: all .2s;
}

.site-header .search-hot-words a:hover {
  background: #ff6700;
  color: #fff;
}
</style>
