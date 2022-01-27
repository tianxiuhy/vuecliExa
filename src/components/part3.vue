<template>
    <div class="part3">
        <div class="title">
            本田
        </div>
        <div >
            <template v-for="i in list" :key="i">
                <div class="col-md-3" >
                    <div class="picture-list-img">
                        <img :src="require(`../imgs/${i.id}.png`)">
                    </div>
                    <div class="brand">{{i.name}}</div>
                </div>
            </template>
        </div>
    </div>
</template>

<script>
    export default {
        name: "part3",
        data(){
            return {
                list:[{id:1,name:"思域"},{id:2,name:"冠道"},{id:3,name:"思铂睿"},{id:4,name:"讴歌"},{id:5,name:"CRV"},{id:6,name:"URV"}]
            }
        },
    }
</script>

<style scoped>
    .part3{
       width: 70%;
    margin-left: 15%;
        background-color: white;
        height: 750px;
    }
    .title{
        height: 2.5em;
        line-height: 2.5em;
        border-bottom: 1px solid #f1f1f1;
        font-weight: 100;
        font-family: "Monospaced Number", "Chinese Quote", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", "Helvetica Neue", Helvetica, Arial, sans-serif;
        font-size: 15px;
        text-align: left;
        width: 100%;
        background-color: white;
        float: left;
    }
    .col-md-3{
        margin-top: 10px;
    }
    .picture-list-img img{
        width: 90%;
        height: 90%;
    }
    .brand{
        text-align: left;
    }
</style>
