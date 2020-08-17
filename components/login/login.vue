<template>
	<view class="container">
		<!-- user and password -->
		<view class="user-table">
			<form class="form">
				<input class="user" type="text" value="" placeholder="用户名或者电子邮箱"/>
				<input class="user" type="password" value="" placeholder="密码"/>
			    <radio class="auto-login"  value="" type="square"/>
				<text class="next">下次自动登录</text>
				<text id="forget-pass">忘记密码?</text>
			</form>
			<image class="eye" src="https://www-static.chinacdn.starbucks.com.cn/prod/assets/icons/icon-hide-password.svg" mode=""></image>
		</view>
		<!-- 滑块 -->
		<!-- 大背景块 -->
		<view class="backBlock">
			<!-- 顶部文字 -->
			<view class="top">
				<view class="left">
					拖动下方滑块完成拼图
				</view>
				<view class="right">
					<text>反馈</text>
					<text>刷新</text>
				</view>
			</view>
			<!-- 背景图 -->
			<image class="imag" src="https://captcha.guard.qcloud.com/cap_union_new_getcapbysig?aid=1253432169&asig=uNqkTTs5X9TDh2xYiA8hSxMUp5FELEOExEALuIltBZcV2PqP42UJLUifXjKqQ7QssLFzfIAMRAsn-gAbQ3SqrjrUXfYlCoHI&captype=&protocol=https&clientype=2&disturblevel=&apptype=&curenv=open&ua=TW96aWxsYS81LjAgKGlQaG9uZTsgQ1BVIGlQaG9uZSBPUyAxM18yXzMgbGlrZSBNYWMgT1MgWCkgQXBwbGVXZWJLaXQvNjA1LjEuMTUgKEtIVE1MLCBsaWtlIEdlY2tvKSBWZXJzaW9uLzEzLjAuMyBNb2JpbGUvMTVFMTQ4IFNhZmFyaS82MDQuMQ==&sess=UKKmFZW5hhhpn0CrZL4hJBsi5ikSIUwl2NmZeDrerDU2I9bK39gDagzWXg2Acsf4obtBrRM5mujBiRVbkIi-yx51D3p9UyXOsAq0KZQfXVC4mxODIT7s-HXKD2mSRdYF_Cz5aijU435P8ijA-2Lifl_PspbCWzK4YUIly5XFLHLddeMtiZuuypee2O5rB__32F6ctB7bXC4*&theme=&sid=6861773658200270669&noBorder=noborder&fb=1&forcestyle=undefined&subsid=3&color=00A862&showtype=embed&uid=&cap_cd=&lang=2052&rnd=210726&TCapIframeLoadTime=23&prehandleLoadTime=76&createIframeStart=1597631175902&rand=0.7475647184562875&websig=553d839bf9e557b005fca43a716667535547593554583c6aa8f1f173edb072e73e01dea3ad086ae929bee01ce5a5759cb2549395ad80a992e68d183ded3940b1&vsig=b01AZNVtxTslsk7YnQzCOckfkniSoPkUaaojb7T918vvOdwc7qp3VSAJoXNoZjBsTrHrsgPoNIs9g7p8BkRmMywb6RNTq38sjvWkcGn45izi3PG5I_dJqhvdQ**&img_index=1" mode=""></image>
		    <image class="small-imag" src="https://captcha.guard.qcloud.com/cap_union_new_getcapbysig?aid=1253432169&asig=uNqkTTs5X9TDh2xYiA8hSxMUp5FELEOExEALuIltBZcV2PqP42UJLUifXjKqQ7QssLFzfIAMRAsn-gAbQ3SqrjrUXfYlCoHI&captype=&protocol=https&clientype=2&disturblevel=&apptype=&curenv=open&ua=TW96aWxsYS81LjAgKGlQaG9uZTsgQ1BVIGlQaG9uZSBPUyAxM18yXzMgbGlrZSBNYWMgT1MgWCkgQXBwbGVXZWJLaXQvNjA1LjEuMTUgKEtIVE1MLCBsaWtlIEdlY2tvKSBWZXJzaW9uLzEzLjAuMyBNb2JpbGUvMTVFMTQ4IFNhZmFyaS82MDQuMQ==&sess=UKKmFZW5hhhpn0CrZL4hJBsi5ikSIUwl2NmZeDrerDU2I9bK39gDagzWXg2Acsf4obtBrRM5mujBiRVbkIi-yx51D3p9UyXOsAq0KZQfXVC4mxODIT7s-HXKD2mSRdYF_Cz5aijU435P8ijA-2Lifl_PspbCWzK4YUIly5XFLHLddeMtiZuuypee2O5rB__32F6ctB7bXC4*&theme=&sid=6861773658200270669&noBorder=noborder&fb=1&forcestyle=undefined&subsid=4&color=00A862&showtype=embed&uid=&cap_cd=&lang=2052&rnd=210726&TCapIframeLoadTime=23&prehandleLoadTime=76&createIframeStart=1597631175902&rand=0.7475647184562875&websig=553d839bf9e557b005fca43a716667535547593554583c6aa8f1f173edb072e73e01dea3ad086ae929bee01ce5a5759cb2549395ad80a992e68d183ded3940b1&vsig=b01AZNVtxTslsk7YnQzCOckfkniSoPkUaaojb7T918vvOdwc7qp3VSAJoXNoZjBsTrHrsgPoNIs9g7p8BkRmMywb6RNTq38sjvWkcGn45izi3PG5I_dJqhvdQ**&img_index=2" mode=""></image>
		    <!-- 滑块 -->
			<!-- 底部长条 -->
			<view class="long"></view>
			<!-- 绿色方块 -->
			<view class="greenBlock">
				|||
			</view>
		</view>
	    <!-- 底部登录按钮 -->
		<view class="login-button">
			登录
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			};
		}
	}
</script>

<style lang="scss">
     .container {
		 background-color: #f7f7f7;
		 padding-bottom: 250rpx;
		 padding-top: 30rpx;
		 .user-table {
			 position: relative;
			 .form {
			 		 .user{
			 			 border-bottom: 1px solid rgba(0,0,0,0.12);
			 			 padding: 40rpx 0 20rpx 0;
			 			 width: 650rpx;
						 margin-left: 40rpx;
			 			 }
						.auto-login {
							 border-radius:16rpx;
							 margin: 50rpx 0 0 40rpx;
						 }
						 .next {
							 font-size: 28rpx;
							 color: rgba(0,0,0,0.56);
						 }
						 #forget-pass {
							 font-size: 26rpx;
							 color: #00a862;
							 margin-left: 300rpx;
						 }
			 }
			 .eye {
				 width: 48rpx;
				 height: 48rpx;
				 position: absolute;
				 top: 160rpx;
				 right: 70rpx;
			 }
		 }
	     .backBlock {
			 width: 654rpx;
			 height: 460rpx;
			 background-color: #fff;
			 box-shadow: 0 1px 1px 1px rgba(0,0,0,0.12);
			 margin: 40rpx auto;
			 position: relative;
			 padding-bottom: 30rpx;
			 .top {
				 display: flex;
				 padding-top: 20rpx;
				 padding-left: 50rpx;
				 position: relative;
				 .left {
					 font-size: 28rpx;
				 }
				 .right {
					 font-size: 24rpx;
					 color: #b3b3b3;
					 position: absolute;
					 right: 25rpx;
					 top: 25rpx;
					 text {
						 margin-right: 20rpx;
					 }
				 }
			 }
			 .imag {
				 width: 560rpx;
				 height: 316rpx;
				 margin: 10rpx 0 0 50rpx;
			 }
			 .small-imag {
				 width: 110rpx;
				 height: 110rpx;
				 position: absolute;
				 top: 120rpx;
				 left: 100rpx;
			 }
			 .long {
				 width: 560rpx;
				 height: 26rpx;
				 background-color: #e4e4e4;
				 border-radius: 14rpx;
				 margin: 40rpx auto;
			 }
			 .greenBlock {
				 width: 108rpx;
				 height: 64rpx;
				 background-color: #008a62;
				 color: #fff;
				 text-align: center;
				 letter-spacing: 5rpx;
				 font-weight: 900;
				 border-radius: 40rpx;
				 position: absolute;
				 bottom: 12rpx;
				 left: 70rpx;
			 }
		 }
	 }
	 .login-button {
		 width: 164rpx;
		 height: 104rpx;
		 font-size: 32rpx;
		 color: rgba(0,0,0,0.38);
		 background-color: #f7f7f7;
		 border-radius: 48rpx;
		 text-align: center;
		 line-height: 104rpx;
		 font-weight: 700;
		 box-shadow: 0 2px 4px 0 rgba(0,0,0,0.38);
		 position: absolute;
		 top: 1150rpx;
		 right: 70rpx;
	 }
</style>
