<template>
  <div class="container">
    <swiper :options="swiperOption" class="wrapper">
      <swiper-slide>
        <div class="headimg">
          <img src="@/assets/icon1.png" />
        </div>
        <p class="name">张三</p>
        <div class="desc">
          <p>2019年10月01日</p>
          <p>向教育基金会捐赠</p>
        </div>
        <p class="money">100000</p>
        <p class="moneyyuan">元</p>
      </swiper-slide>
      <swiper-slide>
        <div class="headimg">
          <img src="@/assets/icon1.png" />
        </div>
        <p class="name">张三</p>
        <div class="desc">
          <p>2019年10月01日</p>
          <p>向教育基金会捐赠</p>
        </div>
        <p class="money">100000</p>
        <p class="moneyyuan">元</p>
      </swiper-slide>
      <swiper-slide>
        <div class="headimg">
          <img src="@/assets/icon1.png" />
        </div>
        <p class="name">张三</p>
        <div class="desc">
          <p>2019年10月01日</p>
          <p>向教育基金会捐赠</p>
        </div>
        <p class="money">100000</p>
        <p class="moneyyuan">元</p>
      </swiper-slide>
      <swiper-slide>
        <div class="headimg">
          <img src="@/assets/icon1.png" />
        </div>
        <p class="name">张三</p>
        <div class="desc">
          <p>2019年10月01日</p>
          <p>向教育基金会捐赠</p>
        </div>
        <p class="money">100000</p>
        <p class="moneyyuan">元</p>
      </swiper-slide>
      <swiper-slide>
        <div class="headimg">
          <img src="@/assets/icon1.png" />
        </div>
        <p class="name">张三</p>
        <div class="desc">
          <p>2019年10月01日</p>
          <p>向教育基金会捐赠</p>
        </div>
        <p class="money">100000</p>
        <p class="moneyyuan">元</p>
      </swiper-slide>
      <swiper-slide>
        <div class="headimg">
          <img src="@/assets/icon1.png" />
        </div>
        <p class="name">张三</p>
        <div class="desc">
          <p>2019年10月01日</p>
          <p>向教育基金会捐赠</p>
        </div>
        <p class="money">100000</p>
        <p class="moneyyuan">元</p>
      </swiper-slide>
      <swiper-slide>
        <div class="headimg">
          <img src="@/assets/icon1.png" />
        </div>
        <p class="name">张三</p>
        <div class="desc">
          <p>2019年10月01日</p>
          <p>向教育基金会捐赠</p>
        </div>
        <p class="money">100000</p>
        <p class="moneyyuan">元</p>
      </swiper-slide>
    </swiper>
    <div class="swiper-button-prev" slot="button-prev">
      <img src="@/assets/arrow-up.png">
    </div>
    <div class="swiper-button-next" slot="button-next">
      <img src="@/assets/arrow-down.png">
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeSwiper',
  data () {
    return {
      swiperOption: {
        direction: 'vertical',
        slidesPerView: 3,
        spaceBetween: 25,
        slidesPerGroup: 3,
        loop: true,
        loopFillGroupWithBlank: true,
        navigation: {
          nextEl: '.swiper-button-next',
          prevEl: '.swiper-button-prev'
        }
      }
    }
  }
}
</script>

<style lang="stylus" scoped>
.container
  position: relative
  .swiper-button-prev
    height: .62rem
    width: .62rem
    background: #fff
    position: absolute
    left: 17.37rem
    top: .65rem
    box-shadow: 0 0 0.15rem #aaa
    display: flex
    justify-content: center
    align-items: center
    img
      width:.48rem
  .swiper-button-next
    height: .62rem
    width: .62rem
    background: #fff
    position: absolute
    right: 1.2rem
    top: 6.7rem
    box-shadow: 0 0 0.15rem #aaa
    display: flex
    justify-content: center
    align-items: center
    img
      width:.48rem
  .wrapper
    padding:.2rem 0 .2rem 2.46rem
    height: 6.7rem
    overflow: hidden
    position: relative
    .swiper-slide
      box-sizing:border-box
      background: #fff
      border-radius: .2rem
      width: 14.28rem
      display: flex
      text-align: center
      align-items: center
      justify-content: center
      padding: 0 .64rem 0 .6rem
      box-shadow: 0 0 0.15rem #aaa
      .headimg
        height: 1.23rem
        width: 1.23rem
        background: blue
        border-radius:.1rem
        overflow: hidden
        img
          height: 1.23rem
          width: 1.23rem
      .name
        font-size: .52rem
        color: #2e2623
        width: 4.42rem
      .desc
        color: #2e2623
        font-size: .4rem
        width: 3.26rem
        line-height: .53rem
      .money
        font-size: .65rem
        color: #2e2623
        flex: 1
        text-align:right
      .moneyyuan
        width: .64rem
        font-size: .65rem
        color: #2e2623
</style>
