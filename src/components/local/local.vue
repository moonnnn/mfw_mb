<template>
  <div>
 <div class="wrap">
    <!-- header -->
    <header class="header">
        <a href="index.html"><i></i></a>
        <div class="logo">
             <h1><a href="" title="马蜂窝">欢迎来到马蜂窝</a></h1>
        </div>
        <a href="denglu.html">登录</a>
    </header>
    <!-- banner -->
   <div class="toutiao">
        <img src="../../assets/img/ttt.jpg" alt="" />
        <span class="jianmianxuzhi">见面须知</span>
   </div>
    <!-- 内容 -->
    <div class="neirong">
        <div class="shenghuo">
        <div class="tupian"><img src="../../assets/img/wKgBs1Z7nFWAJg6SABHGgVmMdJE79.jpeg" alt="" /></div>
             <div class="live">
                 <div class="live-in">
                     <div class="live-in-top">
                         <h5>吃货在狭小的空间吃了很多东西了额</h5>
                         <div class="io" style="color:#ff9d00;font-size:12px;">
                             <span >¥<font style="font-size:14px;">150</font>元/次</span>&nbsp;
                             <span>63人喜欢</span>&nbsp;
                             <span>1人付款</span>
                         </div>
                         <div class="gogoon">租TA<span class="gogo"></span></div>
                     </div>
                     <div class="live-in-bottom">
                        <span class="difang"><i></i>北京土著</span>
                        <span style="color:#e5e5e5">|</span>
                        <span class="biaoqian">
                        <span class="">美食</span>
                        <span>生活小能手</span>
                        <span>纳尼？</span>
                        </span>
                     </div>
                     <span class="toutou"></span>
                 </div>
             </div>
        </div>

        <div class="shenghuo">
        <div class="tupian"><img src="../../assets/img/wKgBs1Z7nFWAJg6SABHGgVmMdJE79.jpeg" alt="" /></div>
             <div class="live">
                 <div class="live-in">
                     <div class="live-in-top">
                         <h5>吃货在狭小的空间吃了很多东西了额</h5>
                         <div class="io" style="color:#ff9d00;font-size:12px;">
                             <span >¥<font style="font-size:14px;">150</font>元/次</span>&nbsp;
                             <span>63人喜欢</span>&nbsp;
                             <span>1人付款</span>
                         </div>
                         <div class="gogoon">租TA<span class="gogo"></span></div>
                     </div>
                     <div class="live-in-bottom">
                        <span class="difang"><i></i>北京土著</span>
                        <span style="color:#e5e5e5">|</span>
                        <span class="biaoqian">
                        <span class="">美食</span>
                        <span>生活小能手</span>
                        <span>纳尼？</span>
                        </span>
                     </div>
                     <span class="toutou"></span>
                 </div>
             </div>
        </div>

        <div class="shenghuo">
        <div class="tupian"><img src="../../assets/img/wKgBs1Z7nFWAJg6SABHGgVmMdJE79.jpeg" alt="" /></div>
             <div class="live">
                 <div class="live-in">
                     <div class="live-in-top">
                         <h5>吃货在狭小的空间吃了很多东西了额</h5>
                         <div class="io" style="color:#ff9d00;font-size:12px;">
                             <span >¥<font style="font-size:14px;">150</font>元/次</span>&nbsp;
                             <span>63人喜欢</span>&nbsp;
                             <span>1人付款</span>
                         </div>
                         <div class="gogoon">租TA<span class="gogo"></span></div>
                     </div>
                     <div class="live-in-bottom">
                        <span class="difang"><i></i>北京土著</span>
                        <span style="color:#e5e5e5">|</span>
                        <span class="biaoqian">
                        <span class="">美食</span>
                        <span>生活小能手</span>
                        <span>纳尼？</span>
                        </span>
                     </div>
                     <span class="toutou"></span>
                 </div>
             </div>
        </div>
        <div class="chaxun">加载更多</div>
    </div>
    <div class="chuzu">

    </div>
</div>
  </div>
</template>

<script>

export default {
}

</script>

<style scoped>
/*头部*/
/*å¤´éƒ¨*/
.header{
    width:100%;
    height:50px;
    border-bottom:1px solid #e5e5e5;
    position:relative;
    overflow:hidden;
    background:#fff;}

.header a i{
    width:10px;
    height:10px;
    display:block;
    border:2px solid #f29406;
    border-right:0;
    border-bottom:0;
    transform:rotate(-45deg);
    position:absolute;
    top:18px;
    left:16px;}

.logo{
    width:81px;
    height:21px;
    background:url(../../assets/img/logo.png) no-repeat;
    background-size:81px auto;
    margin:15px auto;}

.logo a{
    font-size:12px;
    display:block;
    text-indent:-10000em;}

.header a:nth-of-type(2){
    line-height:18px;
    font-size:12px;
    color:#ffa800;
    position:absolute;
    top:15px;
    right:16px;}

/*banner*/
.toutiao{
    position:relative;
    width:100%;
    height:auto;
    background:#eeeeee;}

.toutiao img{
    width:100%;
    height:auto;
    background: url(../../assets/img/ttt.jpg);
    display:block;}

.toutiao .jianmianxuzhi{
    position:absolute;
    width: 78px;
    height: 28px;
    display:block;
    border-radius: 14px;
    border: 1px solid #fff;
    color:#fff;
    right:17px;
    top:7px;
    font-size: 11px;
    text-align: center;
    line-height: 28px;}

.neirong{
    background: #eeeeee;}

.neirong .shenghuo{
    padding:12px;
    box-sizing: border-box;}

.neirong .shenghuo img{
    width:100%;
    height:auto;
    border-radius:5px 5px 0 0;
    display:block;}

.live{
    height:126px;
    background: #fff;
    border-radius: 0 0 5px 5px;
    box-shadow: 0px 2px 0px #dbdbdb;
    position:relative;}

.live-in{
    padding:0 16px;
    box-sizing: border-box;}

.live-in-top{
    height:88px;
    border-bottom:#e5e5e5 solid 1px;}

.live-in-top h5{
    font-size: 16px;
    color:#333333;
    font-weight: normal;
    line-height: 50px;}

.gogoon{
    width: 72px;
    height: 26px;
    border-radius: 2px;
    border: 1px solid #ff9d00;
    color:#ff9d00;
    font-size: 11px;
    text-align: center;
    line-height: 26px;
    float:right;}

.io{
    float:left;}

.gogo{
    width:7px;
    height:7px;
    border-top:1px solid #ff9e00;
    border-right:1px solid #ff9e00;
    display:inline-block;
    transform:rotate(45deg);}

.live-in-bottom{
    height:36px;
    line-height: 36px;
    font-size: 12px;}

.live-in-bottom .difang{
    color:#ff9e00;}

.live-in-bottom .difang i{
    width:16px;
    height:16px;
    display:inline-block;
    background:url(../../assets/img/icon_sprites3.png) -83px -40px;
    background-size:120px auto;
    vertical-align: -3px;
    margin-right: 3px;}

.biaoqian span{
    padding:3px 8px;
    background: #f7f7f7;
    color:#a3a3a3;
    height:18px;
    line-height: 18px;
    border-radius: 4px;}

.toutou{
    display:block;
    width: 60px;
    height: 60px;
    background:url(../../assets/img/wKgB3FEo-q-AVaUjAAAywyOV3XU09.jpeg);
    background-size:60px auto;
    position: absolute;
    right:26px;
    top:-30px;
    border-radius: 50%;}

.chaxun{
    height:34px;
    margin:4px auto;
    border-radius: 3px;
    background: #ff9e00;
    width:70%;
    text-align: center;
    font-size: 14px;
    color:#fff;
    line-height: 34px;
    margin-bottom: 38px;}

</style>
