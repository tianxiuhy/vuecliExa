<template>
    <div class="part2">
            <div class="headline">
                达芬奇汽车出品
            </div>
            <div class="col" style="margin-top: 10px">
                 <a href="https://www.vincicar.net/category/vincicar-soft">
                    <img alt="车型图片" class="_3xwLG" src="http://da-vinci-car.oss-cn-shanghai.aliyuncs.com/www_vincicar_net/categories/vincicar-soft.jpg?x-oss-process=image/resize,w_400">
                    <div class="mrtu">
                        <span>达芬奇软件</span>
                    </div>
                 </a>
            </div>
    </div>
</template>

<script>
    export default {
        name:'picture',
        //props用于获取父组件的传参赋值
        props: [],
        methods:{

        }
    };
</script>

<style scoped>
.mrtu{
    background-color: burlywood;
}
._3xwLG{
    -webkit-text-size-adjust: 100%;
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
    font-weight: 100;
    font-family: "Monospaced Number", "Chinese Quote", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", "Helvetica Neue", Helvetica, Arial, sans-serif;
    line-height: 1.5;
    font-size: 1em!important;
    white-space: normal;
    cursor: pointer;
    color: #222;
    box-sizing: border-box;
    border-style: none;
    vertical-align: middle;
    width: 100%;
    height: auto;
}

.part2{
    width: 70%;
    margin-left: 15%;
    background-color: white;
}
 .headline{
     font-weight: 100;
     font-family: "Monospaced Number", "Chinese Quote", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", "Helvetica Neue", Helvetica, Arial, sans-serif;
     font-size: 1em!important;
     box-sizing: border-box;
     color: #222;
     padding: 0 1em;
     height: 2.5em;
     line-height: 2.5em;
     border-bottom: 1px solid #f1f1f1;
     margin-top: 10px;
     text-align: left;
    }
ul{
    list-style: none;
}
.col{
    margin-top: 30px;
    -webkit-text-size-adjust: 100%;
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
    font-weight: 100;
    font-family: "Monospaced Number", "Chinese Quote", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", "Helvetica Neue", Helvetica, Arial, sans-serif;
    line-height: 1.5;
    color: rgba(0, 0, 0, 0.65);
    font-size: 1em!important;
    box-sizing: border-box;
    display: flex;
    -webkit-box-pack: start;
    justify-content: flex-start;
    flex-wrap: wrap;
    white-space: normal;
}
</style>
