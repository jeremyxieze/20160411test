<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">  
    <meta charset="utf-8">  
    <meta name="format-detection" content="telephone=no">  
    <meta name="apple-mobile-web-app-capable" content="yes">  
    <meta name="apple-mobile-web-app-status-bar-style" content="black">  
      
    <meta http-equiv="Pragma" content="no-cache">  
    <meta http-equiv="Expires" content="-1">  
    <!--移动端版本兼容 -->  
    <script type="text/javascript">  
      var phoneWidth = parseInt(window.screen.width);  
      var phoneScale = phoneWidth / 640;  
      var ua = navigator.userAgent;  
      if (/Android (\d+\.\d+)/.test(ua)) {  
        var version = parseFloat(RegExp.$1);  
        if (version > 2.3) {  
          document.write('<meta name="viewport" content="width=640, minimum-scale = ' + phoneScale + ', maximum-scale = ' + phoneScale + ', target-densitydpi=device-dpi">');  
        } else {  
          document.write('<meta name="viewport" content="width=640, target-densitydpi=device-dpi">');  
        }  
      } else {  
        document.write('<meta name="viewport" content="width=640, user-scalable=no, target-densitydpi=device-dpi">');  
      }  
        
    </script>  
    <meta name="viewport" content="width=640, user-scalable=no, target-densitydpi=device-dpi">  
    <title>invite</title>
	<script src="http://j0.feiheimg.com/?p=plus/1.0.0/jquery-1.10.2.min.js"></script>
	<script src="http://j3.feiheimg.com/m/js/1.0.0/fh.global.js"></script>
	<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0">

	
<style>
@media screen and (min-width:300px){html,body,input{font-size:15px}}
@media screen and (min-width:320px){html,body,input{font-size:16px}}
@media screen and (min-width:340px){html,body,input{font-size:17px}}
@media screen and (min-width:360px){html,body,input{font-size:18px}}
@media screen and (min-width:375px){html,body,input{font-size:18.75px}}
@media screen and (min-width:380px){html,body,input{font-size:19px}}
@media screen and (min-width:400px){html,body,input{font-size:20px}}
@media screen and (min-width:414px){html,body,input{font-size:20.7px}}
@media screen and (min-width:420px){html,body,input{font-size:21px}}
@media screen and (min-width:440px){html,body,input{font-size:22px}}
@media screen and (min-width:460px){html,body,input{font-size:23px}}
@media screen and (min-width:480px){html,body,input{font-size:24px}}
@media screen and (min-width:500px){html,body,input{font-size:25px}}
@media screen and (min-width:520px){html,body,input{font-size:26px}}
@media screen and (min-width:540px){html,body,input{font-size:27px}}
@media screen and (min-width:560px){html,body,input{font-size:28px}}
@media screen and (min-width:580px){html,body,input{font-size:29px}}
@media screen and (min-width:600px){html,body,input{font-size:30px}}
@media screen and (min-width:620px){html,body,input{font-size:31px}}
@media screen and (min-width:640px){html,body,input{font-size:32px}}
@media screen and (min-width:660px){html,body,input{font-size:33px}}
@media screen and (min-width:680px){html,body,input{font-size:34px}}
@media screen and (min-width:700px){html,body,input{font-size:35px}}
@media screen and (min-width:720px){html,body,input{font-size:36px}}
@media screen and (min-width:740px){html,body,input{font-size:37px}}
@media screen and (min-width:760px){html,body,input{font-size:38px}}
@media screen and (min-width:780px){html,body,input{font-size:39px}}
@media screen and (min-width:800px){html,body,input{font-size:40px}}
@media screen and (min-width:1024px){html,body,input{font-size:51.2px}}
@media screen and (min-width:1349px){html,body,input{font-size:67.45px}}






ul {list-style: none;margin:0; padding:0;}
a{ text-decoration:none;} 
p{
	margin:0;
	padding:0;
}
body{
	background-color:#fff;
	font-size:0.12rem;
	font-family:"Open Sans",Arial,"Hiragino Sans GB","Microsoft YaHei","微软雅黑","STHeiti","WenQuanYi Micro Hei",SimSun,sans-serif;
	-webkit-font-smoothing:antialiased;
	margin:0;
	padding:0;
	vertical-align:baseline;
}

/*MGM邀请页面begin*/
.m-inv-body{
	width:6.4rem;
	margin:0 auto;
}
.inv-top-bg{
	background:url(http://i0.feiheimg.com/img/m/mgm0406/invite_02.jpg);
	background-size:6.4rem 1.75rem;
	background-repeat:no-repeat;
	height:1.75rem;
}
.inv-center-bg{
	background:url(http://i1.feiheimg.com/img/m/mgm0406/invite_03.jpg);
	background-size:6.4rem 3.37rem;
	background-repeat:no-repeat;
	height:3.37rem;
}
.inv-slogan{
	background:url(http://i2.feiheimg.com/img/m/mgm0406/inv-nav-pic.png);
	background-repeat:no-repeat;
	background-size:6.4rem 1.45rem;;
	height:1.45rem;
	position:relative;
	z-index:9999;
}

.inv-data{
height:0.46rem;
	float:right;
	font-size:0.2rem;
	line-height:0.8rem;
	color:#000;
	padding:0.07rem 0.3rem 0.15rem 0.3rem;
	background:url(imv-white.png);
	background-repeat:no-repeat;
	background-size:100%;
	border-radius:0.5rem 0rem 0rem 0.5rem;
	margin-top:-0.3rem;
}
.inv-bottom{
	background:#3bb276;
	padding-top:0.5rem;
	padding-bottom:2rem;
}
.inv-bottom-pic{
	height:3.5rem;
	padding-left:0.2rem;
	position:relative;
	overflow:hidden;
}
.inv-bottom-pic img{
	float:left;
	border-radius:1rem;
	margin-right:0.5rem;
	border:0.05rem solid #15804b;
	width:0.87rem;
	height:0.87rem;
	margin-top:0.17rem;
}
.inv-bottom-pic-div{
	background:#15804b;
	padding:0.1rem 0.3rem;
	text-indent:0.6rem;
	font-size:0.3rem;
	color:#fff;
	border-radius:0.1rem;
	width:4rem;
	float:left;
	position:relative;
}
.inv-abs{
	width: 0;
    height: 0;
    border-top: 0.3rem solid transparent;
    border-right: 0.4rem solid #15804b;
    border-bottom: 0.3rem solid transparent;
	position:absolute;
	left:-0.39rem;
	top:0.3rem;
	background:#3bb276 !important;
	padding-bottom:0.05rem;
}
.inv-last-div{
	clear:both;
	display:block;
	font-size:0.3rem;
	line-height:0.36rem;
	text-align:center;
	color:#fff;
	margin-left:0.25rem;
	margin-right:0.15rem;
	padding:0.2rem 0rem 0.2rem 0rem;
	background:#ffb800;
	border-radius:0.1rem;
	box-shadow: 0rem 0.06rem 0rem #b06b00;
}
/*MGM邀请页面End*/
</style>
</head>
<body>
   <div class="m-inv-body">
		<div class="inv-top-bg"></div>
		<div class="inv-center-bg">
			<div class="inv-slogan"></div>
			<div class="inv-data">
				活动时间2016.3.6~2016.4.16
			</div>
		</div>
		<div class="inv-bottom">
			<div class="inv-bottom-pic">
				<img src="http://i2.feiheimg.com/img/m/mgm0406/useImg.png">
				<div class="inv-bottom-pic-div">亲爱的XX,我家宝宝一直吃飞鹤奶粉，身体棒棒的！我刚争取到一个飞鹤官网“送530元红包+免费领一罐超高端 星飞帆3段体验装"的机会，现在分享给你，快 去领取吧！
					<div class="inv-abs"></div>
				</div>
			</div>
			<a href="javascript:void(0)" class="inv-last-div">
				领取我的专享大礼包
			</a>
		</div>
   </div>
</body>
</html>
