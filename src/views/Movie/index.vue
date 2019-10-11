<template>
    <div>
        
        <navBar />
        <h1>我是电影页面</h1>
        <tabBar />
    </div>
</template>

<script>
import navBar from '@/components/navBar/navBar'
import tabBar from '@/components/tabBar/tabBar'

export default {
    name :'movie',
    components : {
        navBar,
        tabBar
    }
}
</script>

<style lang="">
    
</style>