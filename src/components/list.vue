<template >
<div  class="container-fluid" style="display:none" >
    <div class="col-md-10" v-on:click="hide()"></div>
    <div class="col-md-2">
            <div class="listBtn" id="listBtnTop">
                 <a href="/" >首页</a>
            </div>
        
            <div class="listBtn" id="lbt1">
                <div v-on:click="showlist1()">
                    达芬奇汽车出品<span class="caret"></span>
                </div>
                <ul class="droplist1" style="display:none">
                    <li>达芬奇软件</li>
                </ul>
            </div>
        
            <div class="listBtn" id="lbt2">
                       <div v-on:click="showlist2()">
                           本田<span class="caret"></span>
                       </div>
                        <ul class="droplist2" style="display:none">
                            <li>思域</li>
                            <li>冠道</li>
                            <li>思铂睿</li>
                            <li>讴歌CDX</li>
                            <li>CRV</li>
                            <li>URV</li>
                        </ul>
            </div>

            <div class="listBtn">
                 <a href="https://www.vincicar.net/ucenter/account_find">小助手账号找回</a>
            </div>

           <div class="listBtn">
                <a href="https://www.vincicar.net/ucenter/password">密码修改</a>
            </div>
    </div>
</div>
</template>
<script>
import $ from 'jquery'
export default {
    data(){
        return{
        }
    },
    props:{
        
    },
    methods:{
        hide(){
            $(".container-fluid").css("display","none")
        },
        showlist1(){
            if($(".droplist1").css("display")=="none"){
                $(".droplist1").css("display","block")
            }else{
                $(".droplist1").css("display","none")
            }
        },
        showlist2(){
            if($(".droplist2").css("display")=="none"){
                $(".droplist2").css("display","block")
            }else{
                $(".droplist2").css("display","none")
            }
        }
    }
};
</script>
<style>
.col-md-10{
    width: 87.5%;
    display: inline;
    z-index: 100000;
    position:fixed;
    left:0;
    bottom:0;
	height:100%;
    background:#000000; 
    opacity:0.2;
    -moz-opacity:0.8; 
}
.col-md-2{
    width: 12.5%;
  display: inline;
    z-index: 100000;
    position:fixed;
    right:0;
    bottom:0;
	height:100%;
    background:white; 
}
.menu-item{
    list-style: none;
    padding-bottom: 10px;
    padding-top: 25px;
    float: left;
}
.caret{
  margin-right: 10px;
}
.droplist1{
    list-style: none;
    padding-top: 15px;
}
.droplist2{
    padding-top: 15px;
    list-style: none;
}
.listBtn{
    text-align: left;
    display: block;
    padding-top: 20px;
    margin-left: 30px;
    font-size: 14px;
    color: #4c8bc0;
}
.droplist2 li{
    padding-top: 20px;
    margin-left: -30px;
}
.droplist1 li{
    padding-top: 20px;
    margin-left: -30px;
}
#listBtnTop{
    display: block;
    margin-top: 19px;
}
.dropdownmenu{
    display: none;
}
.caret{
    float: right;
    margin-top: 9px;
}
#lbt1 :hover{
    cursor: pointer;
}
#lbt2 :hover{
    cursor: pointer;
}
</style>

