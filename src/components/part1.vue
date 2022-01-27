<template >
    <div class="part1">
        <div >
            <div class="inputbox">
                <div >
                    <input type="text" class="form-control" placeholder="输入要查找的车型或模块">
                </div>
            </div>
            <div class="screen">
                <img src="../imgs/jup.png" alt="">
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "search"
    }
</script>

<style scoped>
    .part1{
     width: 70%;
    margin-left: 15%;
    background-color: white;
    }
    .inputbox{
        padding-top: 10px;
        height: 30px;
        text-align: center;
    }
    .screen{
    padding-top: 20px;
    background-color: #fff;
    width: 100%;
    height: 300px;
    }
    .screen img{
    margin-top: 15px;
    width:55%;
    height:90%;
    }
    .form-control{
        -webkit-text-size-adjust: 100%;
        -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
        -webkit-box-direction: normal;
        overflow: visible;
        font-family: "Monospaced Number", "Chinese Quote", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", "Helvetica Neue", Helvetica, Arial, sans-serif;
        box-sizing: border-box;
        margin: 0;
        list-style: none;
        position: relative;
        display: inline-block;
        padding: 4px 11px;
        width: 80%;
        height: 32px;
        font-size: 14px;
        line-height: 1.5;
        color: rgba(0, 0, 0, 0.65);
        background-color: #fff;
        background-image: none;
        border: 1px solid #d9d9d9;
        border-radius: 4px;
        transition: all .3s;
        -webkit-appearance: none;
        touch-action: manipulation;
        -webkit-box-flex: 1;
        flex: 1 1;
    }
</style>
