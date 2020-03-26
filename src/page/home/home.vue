<template>
  <div>
    <home-header></home-header>
    <home-hero-container></home-hero-container>
  </div>
</template>

<script>
import HomeHeader from './components/homeHeader'
import HomeHeroContainer from './components/homeHeroContainer'
export default {
  name: 'home',
  components: {
    HomeHeader,
    HomeHeroContainer
  }
}
</script>

<style>
body {
  min-width: 1226px;
  margin: 0;
  font: 14px/1.5 Helvetica Neue,Helvetica,Arial,Microsoft Yahei,Hiragino Sans GB,Heiti SC,WenQuanYi Micro Hei,sans-serif;
  color: #333;
}

ul {
  margin: 0;
  padding: 0;
  list-style: none;
}

a {
  text-decoration: none;
}

.clearfix::after {
  content: '';
  display: block;
  clear: both;
}
</style>
