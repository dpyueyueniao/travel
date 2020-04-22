<template>
 <div class="swiper">
  <div 
   class="aaa"
   :class="{transform: xxx}"
  >
   <img src="item.src"/>
  </div>
 </div>
</template>

<script>
export default {
 name: 'SwiperItem',
 data () {
  return{
   xxx: `translateX(${100 * this.index}%)`
  }
 }, 
 props: [
  'item', 
  'index'
 ]
}
</script>

<style lang="stylus" scoped>
 .aaa
  width 30%
  height 31.25vw
</style>