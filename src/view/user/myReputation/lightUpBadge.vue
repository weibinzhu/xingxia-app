<template>
  <div class="lightUpBadgeWrapper">
    <v-header title="点亮徽章"></v-header>
    <img class="headImg" src="/static/caseDetail.png"/>
    <div class="lightUpBadgeNotice">
      <div class="lightUpBadgeNoticeText">
        <img class="lightUpBadgeIcon" src="/static/kefu@3x.png"/>如有疑问，请咨询：020-34479909(9:00-18:00)
      </div>
      <img class="lightUpBadgeArrow" src="/static/arrow-right-gray.png"/>
    </div>
    <div class="lightUpBadgeIntro">
      <div class="lightUpBadgeIntroTitle">
        徽章介绍
      </div>
      <div class="lightUpBadgeIntroContent">
        巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉巴拉
      </div>
    </div>
    <div class="lightUpBadgePrice">
      <img src="/static/kefu@3x.png"/>
      <span>￥80 / 年</span>
    </div>
    <div class="lightUpBadgeAgreement">
      <input id="agreement" name="agreement" type="checkbox"/>
      <label for="agreement" class="agreement">
        <div></div>
      </label>
      <a href="http://www.baidu.com">阅读并同意《行峡网平台服务协议》</a>
    </div>
    <div class="lightUpBadgeBtn">
      微信支付
    </div>
  </div>
</template>

<script type="text/ecmascript-6">
  import header from '@/components/v-header/v-header'

  export default {
    components: {
      'v-header': header
    }
  }
</script>

<style lang="stylus" rel="stylesheet/stylus" scoped>
  @import "../../../common/style/fun.styl"
  .lightUpBadgeWrapper
    display: flex
    flex-direction: column
    min-height: 100vh
    font-size: px2-2-rem(32)
    background-color: #f8f8f8
    .headImg
      height: px2-2-rem(380)
    .lightUpBadgeNotice
      display: flex
      justify-content: space-between
      align-items: center
      height: px2-2-rem(88)
      padding: 0 px2-2-rem(30)
      background-color: #ffffff
      margin-bottom: px2-2-rem(24)
      .lightUpBadgeNoticeText
        display: flex
        align-items: center
        font-size: px2-2-rem(26)
        color: #666666
      .lightUpBadgeIcon
        width: px2-2-rem(50)
        margin-right: px2-2-rem(20)
      .lightUpBadgeArrow
        height: px2-2-rem(24)
        width: px2-2-rem(16)
    .lightUpBadgeIntro
      display: flex
      flex-direction: column
      padding: px2-2-rem(20) px2-2-rem(30)
      margin-bottom: px2-2-rem(20)
      background-color: #ffffff
      .lightUpBadgeIntroTitle
        height: px2-2-rem(60)
        line-height: px2-2-rem(60)
        color: #353535
      .lightUpBadgeIntroContent
        color: #999999
    .lightUpBadgePrice
      display: flex
      flex-direction: row
      align-items: center
      padding: 0 px2-2-rem(30)
      height: px2-2-rem(88)
      background-color: #ffffff
      img
        width: px2-2-rem(50)
        margin-right: px2-2-rem(10)
      span
        font-size: px2-2-rem(36)
        color: #f0724f
    .lightUpBadgeAgreement
      display: flex
      flex-direction: row
      align-items: center
      height: px2-2-rem(50)
      padding: 0 px2-2-rem(30)
      a
        color: #999999
        font-size: px2-2-rem(26)
      .agreement
        display: block
        height: px2-2-rem(30)
        width: px2-2-rem(30)
        border: 2px solid #e5e5e5
        margin-right: px2-2-rem(20)
      input[type=checkbox]
        display: none
      input[type=checkbox]:checked + .agreement
        div
          box-sizing: border-box
          width :0
          height :0
          border-top: 10px solid red
          border-left: 5px solid transparent
          border-right: 5px solid transparent
    /*background-color :red*/
    .lightUpBadgeBtn
      position: fixed
      bottom: 0
      width: 100%
      height: px2-2-rem(86)
      line-height: px2-2-rem(86)
      color: #ffffff
      font-size: px2-2-rem(32)
      text-align: center
      background-color: #00a0e9
</style>
