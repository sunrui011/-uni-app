<template>
	<view class="container">
		<!-- 顶部文字区域 -->
		 <view class="top">
		 	<view class="title">
		 		登录或创建一个新帐户 🌟
		 	</view>
			<view class="login-line">
				<text class="login" @click="loginHandel()">登录</text>
				<text class="resgister">注册</text>
				<text class="about">关于星享俱乐部</text>
			</view>
		 </view>
		 <!-- 占位区域 -->
		 <Login class='one' style='display: none;'></Login>
		 <Register class='two' style='display: none;'></Register>
		 <About class='three'></About>
	</view>
</template>

<script>
	import Register from '../../components/register/register'
	import Login from '../../components/login/login'
	import About from '../../components/about/about'
	var btn = document.getElementsByClassName('login');
	export default {
		data() {
			return {
			
			};
		},
		components:{
			Login,
			Register,
			About
		},
		methods:{
			loginHandel(){
				var ast = document.getElementsByClassName('login')
				ast[0].style.fontWeight = 700
				ast[0].style.color = rgba(0,0,0)   
			}
		}
	}
</script>

<style lang="scss">
    .container {
		.top {
			.title {
				font-size: 44rpx;
				font-weight: 900;
				margin: 30rpx 0 0 30rpx;
			}
		}
		.login-line{
			font-size: 32rpx;
			color: rgba(0,0,0,0.56);
			margin: 40rpx 0 20rpx 0;
			text {
				margin: 0rpx 0rpx 0rpx 30rpx;
			}
	}
}
.login-active {
	color: red;
}
</style>
