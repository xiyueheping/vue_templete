<template>
<div id="two-box">
   <h1>页面2</h1>
</div>
</template>
<script>
export default {
    props:[],
    data:function(){
        return{}
    },
    methods:{}
}
</script>
<style scoped>
/* 使用scoped声名的样式只在当前组件有效 */
#two-box{
    padding-top: 40px;
    width: 500px;
    height: 200px;
    margin: 0 auto;
    background-color: blueviolet;
    padding-top: 40px;
}
</style>