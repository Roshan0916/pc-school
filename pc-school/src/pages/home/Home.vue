<template>
  <div class="bg">
    <p class="title">浙江科技学院教育基金会捐赠鸣谢</p>
    <p class="desc">ZUSTEF DONATION ACKNOWLEDGMENTS</p>
    <home-swiper></home-swiper>
  </div>
</template>

<script>
import HomeSwiper from './components/Swiper'
export default {
  components: {
    HomeSwiper
  }
}
</script>

<style lang="stylus" scoped>
.bg
  background: url('~@/assets/bg.png') center center no-repeat
  background-size: 100% 100%
  height: 10.8rem
  position: fixed
  width: 19.2rem
  .title
    font-size: .75rem
    line-height: .77rem
    letter-spacing: .15rem
    color: #2e2623
    text-align: center
    margin-top: 1.04rem
  .desc
    font-size: .25rem
    letter-spacing: .06rem
    color: #2e2623
    margin-top: .15rem
    margin-bottom:.3rem
    text-align: center
</style>
