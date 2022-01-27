<template>
    <nav class="navbar">
        <div class="navm1">
            <img class="_1Gy1t" alt="达芬奇汽车Logo" src="https://www.vincicar.net/assets/c079af1d.png">
            <img class="MShvm" alt="达芬奇汽车Logo" src="https://www.vincicar.net/assets/fb8999cd.png">
        </div>
        <div class="navm2">
            <div class="iconcluster">
                <img src="https://www.vincicar.net/assets/ed8153ce.png" class="_3H0MT" style="width:1.8em;height:1.8em" alt="达芬奇汽车微信图标">
            </div>
            <a href="https://info.vincicar.com" >
                <img src="../imgs/icon1.png">
            </a>
            <a id="listA" v-on:click="closeHandler()">
                <img src="../imgs/icon2.png">
            </a>
        </div>
    </nav>
    <list/>
</template>

<script>
import list from './list.vue';
import $ from 'jquery';
export default {
  components: { list },
        name: "nav",
        methods:{
                closeHandler() {
                 $(".container-fluid").css("display","block")
            },
        data () {
            return {
            };
        }
        }
    }
</script>

<style scoped>
._1Gy1t{
    -webkit-text-size-adjust: 100%;
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
    font-weight: 100;
    font-family: "Monospaced Number", "Chinese Quote", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", "Helvetica Neue", Helvetica, Arial, sans-serif;
    line-height: 1.5;
    font-size: 1em!important;
    -webkit-box-direction: normal;
    cursor: pointer;
    color: #fff;
    box-sizing: border-box;
    border-style: none;
    vertical-align: middle;
    height: 2em;
    margin-right: .5em;
}
.MShvm{
    -webkit-text-size-adjust: 100%;
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
    font-weight: 100;
    font-family: "Monospaced Number", "Chinese Quote", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", "Helvetica Neue", Helvetica, Arial, sans-serif;
    line-height: 1.5;
    font-size: 1em!important;
    -webkit-box-direction: normal;
    cursor: pointer;
    color: #fff;
    box-sizing: border-box;
    border-style: none;
    vertical-align: middle;
    height: 1.6em;
}
.navm1{
    display: inline;
    line-height:75px ;
}
.navm2{
    display: inline;
    line-height:75px ;
    padding-left: 700px;
}
.navbar {
    background-color: rgb(46, 46,46);
    height: 75px;
    border-bottom:  8px solid orange ;
    display: block;
}
.iconcluster{
    -webkit-text-size-adjust: 100%;
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
    font-weight: 100;
    font-family: "Monospaced Number", "Chinese Quote", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", "Helvetica Neue", Helvetica, Arial, sans-serif;
    line-height: 1.5;
    color: rgba(0, 0, 0, 0.65);
    font-size: 1em!important;
    -webkit-box-direction: normal;
    box-sizing: border-box;
    touch-action: manipulation;
    display: inline;
    cursor: pointer;
    padding: 10px;
}

#listA :hover{
    cursor: pointer;
}

</style>
