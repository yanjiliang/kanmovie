<template>
    <div>
        
        <navBar />
        <h1>我是影院</h1>
        <tabBar />
    </div>
</template>

<script>
import navBar from '@/components/navBar/navBar'
import tabBar from '@/components/tabBar/tabBar'


export default {
    name :'cinema',
    components : {
        navBar,
        tabBar
    }
}
</script>

<style lang="">
    
</style>