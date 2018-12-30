<template>
    <div class="header">
        <div class="header-left">
            <div class="iconfont icon-back"></div>
        </div>
        <div class="header-input">
            <span class="iconfont icon-search"></span>
            <span class="text">输入城市/景点/游玩主题</span>
        </div>
        <div class="header-right">
            <span class="text">城市</span>
            <span class="iconfont icon-arrow"></span>
        </div>
    </div>
</template>
<script>
export default {
    name: 'Header'
}
</script>
<style lang="stylus" scoped>
    @import '~styles/variables.styl'
    .header
        background: $bgColor
        height: .86rem
        line-height: .86rem
        display: flex
        .header-left
            width: .64rem
            .icon-back
                text-align: center
        .header-input
            flex: 1
            height: .64rem
            line-height: .64rem
            margin-top: .12rem
            background: #fff
            border-radius: .1rem
            padding-left: .2rem
        .header-right
            width: 1.24rem
            text-align: center
            .icon-arrow 
                font-size: .25rem
</style>



