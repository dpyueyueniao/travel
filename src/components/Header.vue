<template>
  <div class="header">
    <div class="header-left">
      <div class="iconfont back-icon">&#xe624;</div>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe632;</span>
      输入城市/景点/游玩主题
    </div>
    <div class="header-right">
      城市
      <span class="iconfont arrow-icon">&#xe62b;</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
  @import '~@/assets/styles/varibles.styl'
 .header
  display flex
  line-height .86rem
  background $bgColor
  color #fff
  justify-content space-between
  .header-left
    width .64rem
    .back-icon
      text-align center
      font-size .4rem
  .header-input
    flex 1
    height .64rem
    line-height .64rem
    border-radius .1rem
    margin-top .12rem
    margin-left .2rem
    padding-left .2rem
    background #fff
    color #ccc
  .header-right
    width 1.24rem
    text-align center
    .arrow-icon
      font-size .24rem
</style>
