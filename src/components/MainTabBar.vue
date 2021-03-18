<template>
<tab-bar>
     <tab-bar-item path='/home'>
        <img slot="item-icon" src="@/assets/img/tebbar/shouye.svg" alt="">
        <img slot="item-icon-active" src="../assets/img/tebbar/shouye_active.svg" alt="">
         <div slot="item-text">首页</div>   
     </tab-bar-item>
     <tab-bar-item path='/category'>
        <img slot="item-icon" src="../assets/img/tebbar/leimupinleifenleileibie.svg" alt="">
        <img slot="item-icon-active" src="../assets/img/tebbar/leimupinleifenleileibie_active.svg" alt="">
         <div slot="item-text">分类</div> 
     </tab-bar-item>
     <tab-bar-item path='shopcart'>
        <img slot="item-icon" src="../assets/img/tebbar/gouwuchekong.svg" alt="">
        <img slot="item-icon-active" src="../assets/img/tebbar/gouwuchekong_active.svg" alt="">
         <div slot="item-text">购物车</div> 
     </tab-bar-item>
     <tab-bar-item path='/profile'> 
        <img slot="item-icon" src="../assets/img/tebbar/wode.svg" alt="">
        <img slot="item-icon-active" src="../assets/img/tebbar/wode_active.svg" alt="">
         <div slot="item-text">我的</div> 
     </tab-bar-item>
   </tab-bar>
</template>

<script>
import TabBar from './tabbar/TabBar';
import TabBarItem from './tabbar/TabBarItem'
    export default {
        name:"MainTabBar",
        components: {
        TabBar,
        TabBarItem
  }
    }
</script>

<style  scoped>

</style>