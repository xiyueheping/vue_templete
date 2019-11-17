<template>
<div id="one-box">
    <h1>页面1（主页部分）</h1>
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
<style scoped >
/* 引入scoped后当前文件的样式代码只在当前文件生效，不会影响其他组件的样式 */
#one-box{
    padding-top: 40px;
    width: 500px;
    height: 200px;
    margin: 0 auto;
    background-color: green;
}
</style>