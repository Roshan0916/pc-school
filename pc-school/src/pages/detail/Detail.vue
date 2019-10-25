<template>
  <div class="bg">
    <div class="card">
      <div class="title">
        <p>感谢您的捐赠</p>
        <img src="@/assets/return.png" />
      </div>
      <div class="avater">
        <div class="avater-box">
          <img src="@/assets/icon1.png" />
        </div>
        <div class="desc-box">
          <p class="name">李四</p>
          <p class="time">2019年10月1日向教育基金会捐赠</p>
          <div class="money">
            <p>500元</p>
          </div>
        </div>
      </div>
      <div class="content">感谢此次捐赠的各位科大校友，是你们的捐赠让大家觉得浙科大这个大家庭的温暖，是你们的募捐让大家感受到了坚强与团结的力量，是你们的募捐，让学校有更加好的发展。谨代表校友之家的全体人员向捐赠的校友致以最诚挚的谢意，谢谢你们。
</div>
      <p class="content-desc">浙江科技学院教育基金会</p>
      <p class="content-time">2019年10月1日</p>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="stylus" scoped>
.bg
  background: url('~@/assets/bg.png') center center no-repeat
  background-size: 100% 100%
  height: 10.8rem
  position: fixed
  width: 19.2rem
  display: flex
  justify-content: center
  align-items: center
  .card
    width:14.18rem
    height 8.03rem
    background: #fff
    border-radius: .2rem
    box-shadow: 0 0 0.15rem #aaa
    .title
      height 2rem
      line-height: 2rem
      text-align:center
      letter-spacing: .17rem
      font-size: .7rem
      position:relative
      img
        position: absolute
        height:.35rem
        width:.35rem
        right: .28rem
        top:.28rem
    .avater
      height 2.48rem
      padding-left:1rem
      display:flex
      .avater-box
        height 2.48rem
        width:2.48rem
        overflow:hidden
        border-radius:.2rem
        img
          height 2.48rem
          width: auto
      .desc-box
        margin-left:1rem
        .name
          font-size:.45rem
          letter-spacing: .02rem
          padding-bottom:.3rem
        .time
          font-size:.45rem
          padding-bottom:.4rem
          letter-spacing: .04rem
        .money
          height:.92rem
          width: auto
          background: #2e2624
          border-radius:.2rem
          font-size:.62rem
          color:#fff
          display: inline-block
          p
            line-height:.92rem
            text-align:center
            padding:0 .7rem 0 .7rem
    .content
      font-size: .29rem
      margin:.7rem 1.02rem 0 1.02rem
      line-height: .49rem
      letter-spacing: .01rem
    .content-desc
      text-align: right
      margin-top: .35rem
      margin-right:1rem
      font-size: .29rem
    .content-time
      text-align: right
      font-size: .29rem
      margin-right:1rem
      line-height: .64rem
</style>
