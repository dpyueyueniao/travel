<template>
   <div class="wrapper">
      <swiper-item  
         v-for="(item, index) in list"
         :item="item"
         :index="index"
         :key="index"
      >
      </swiper-item>
   </div>
</template>

<script>
import SwiperItem from './Swiper_item.vue'
export default {
   name:'HomeSwiper', 
   components: {
      SwiperItem
   }, 
   data () {
      return{
         list: [1]
      }
   },  
   
}
</script>

<style lang="stylus" scoped>
   .wrapper
      background #eee
      height 31.25vw
</style>