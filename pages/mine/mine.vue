<template>
	<view class="container">
		<!-- 顶部文字区域 -->
		 <view class="top">
		 	<view class="title">
		 		登录或创建一个新帐户 🌟
		 	</view>
			<view class="login-line">
				<text :class="{login:isLogin}" @click="loginHandel()">登录</text>
				<text @click="registerHandel()" :class="{register:isResgister}">注册</text>
				<text :class="{about:isAbout}" @click="aboutHandel()">关于星享俱乐部</text>
			</view>
		 </view>
		 <!-- 占位区域 -->
		 <Login :class="{textLogin:istextLogin,noneLogin:isnoneLogin}"></Login>
		 <Register :class='{textRegister:istextRegister,noneRegister:isnoneRegister}'></Register>
		 <About :class='{textAbout:istextAbout,noneAbout:isnoneAbout}'></About>
	</view>
</template>

<script>
	import Register from '../../components/register/register'
	import Login from '../../components/login/login'
	import About from '../../components/about/about'
	export default {
		data() {
			return {
			   isLogin:true,
			   isResgister:false,
			   isAbout:false,
			   
			   istextLogin:true,
			   istextRegister:false,
			   istextAbout:false,
			   
			   isnoneLogin:false,
			   isnoneRegister:true,
			   isnoneAbout:true
			};
		},
		components:{
			Login,
			Register,
			About
		},
		onLoad() {
			this.istextLogin = true
		},
		methods:{
			loginHandel(){
				this.isResgister = false
				this.isAbout = false
				this.isLogin = true
				this.istextLogin = true
				this.isnoneLogin = false
				this.isnoneAbout = true
				this.isnoneRegister = true
				
			},
			registerHandel(){
				this.isResgister = true
				this.isAbout = false
				this.isLogin = false
				this.isnoneRegister = false
				this.istextLogin = false
				this.isnoneLogin = true
				this.isnoneAbout = true
			},
			aboutHandel(){
				this.isResgister = false
				this.isAbout = true
				this.isLogin = false
				this.isnoneRegister = true
				this.isnoneAbout = false
				this.istextAbout = true
				this.istextLogin = false
		}
	},
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
.login {
	color: #000;
	font-weight: 900;
}
.register {
	color: #000;
	font-weight: 900;
}
.about {
	color: #000;
	font-weight: 900;
}
.textLogin {
	display: block;
}
.textRegister {
	display: block;
}
.textAbout {
	display: block;
}
.noneLogin {
	display: none;
}
.noneRegister {
	display: none;
}
.noneAbout {
	display: none;
}
</style>
