<template>
    <div class="nav-list">
        <router-link to="/Content">go to first page</router-link>

        <!-- 将路由匹配到的组件渲染到这里。不写的话点击连接没有内容出现。-->
			<router-view></router-view>
    </div>
</template>

<script>
export default {
  name: "Nav"
}
</script>

<style scoped>
.nav-list{
    width: 100%;
    height: 500px;
}
</style>