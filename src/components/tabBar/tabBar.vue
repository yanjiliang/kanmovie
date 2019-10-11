<template>
  <div>
    <van-tabbar v-model="active">
      <van-tabbar-item icon="home-o">
          <router-link to='/movie'>电影</router-link>
      </van-tabbar-item>
      <van-tabbar-item icon="search">
          <router-link to='/cinema'>影院</router-link>
      </van-tabbar-item>
      <van-tabbar-item icon="friends-o">
          <router-link to='/mine'>我的</router-link>
      </van-tabbar-item>
      
    </van-tabbar>
  </div>
</template>

<script>
export default {
  name: "tabBar",
  data(){
      return{
          active:0
      }
  }
};
</script>

<style lang="">
</style>