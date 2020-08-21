<template>
	<view class="container">
		<!-- logo -->
		<image class="logo" src="https://www-static.chinacdn.starbucks.com.cn/prod/assets/images/logo.svg" mode=""></image>
	    <!-- 叉叉 -->
		<image class="error" src="https://www-static.chinacdn.starbucks.com.cn/prod/assets/icons/icon-close.svg" mode=""></image>
		<!-- 横线上边 -->
		<view class="same">
			<view @click="goMenDian()" class="two">门店</view>
			<view class="five" @click="goClub()">星享俱乐部</view>
			<view class="two" @click="goMenu()">菜单</view>
		</view>
		<!-- 中间线 -->
		<view class="line">		</view>
		<!-- 下边内容 -->
		<view class="same" id="bottom">
			<view class="seven">星巴克移动应用</view>
			<view class="three">星礼卡</view>
			<view class="five">星巴克甄选</view>
			<view class="nine">啡快 - 在线点 到店取</view>
			<view class="three">专星送</view>
			<view class="five">咖啡星讲堂</view>
			<view class="six">上海烘焙工坊</view>
			<view class="five">关于星巴克</view>
			<view class="four">帮助中心</view>
		</view>
	    <!-- 线 -->
		<view class="line"></view>
		<!-- 底部logo -->
		<view class="bottom-button">
			<!-- 登录 -->
			<view class="left">
				<image src="https://www.starbucks.com.cn/assets/icons/icon-account.svg" mode=""></image>
			    <view>登录</view>
			</view>
			<!-- 注册 -->
			<view class="right">
				注册
			</view>
		</view>
	   <!-- 底部的字 -->
	   <view class="bottom-text">
	   	  <view class="">English</view>
		  <view class="">隐私政策</view>
		  <view class="">使用条款</view>
	   </view>
	</view> 
</template>

<script>
	export default {
		data() {
			return {
				
			};
		},
	    methods:{
			goMenDian(){
				uni.switchTab({
					url:'../store/store'
				})
			},
			goClub (){
				uni.switchTab({
					url:'../mine/mine'
				})
			},
			goMenu(){
				uni.switchTab({
					url:'../menu/menu'
				})
			}
		}
	}
</script>

<style lang="scss">
    .container {
		.logo {
			width: 72rpx;
			height: 72rpx;
			margin: 30rpx 0 0 30rpx;
		}
		.line {
			width: 750rpx;
			height: 2rpx;
			background-color: rgba(0,0,0,0.12);
			margin-top: 30rpx;
		}
		.same {
			font-size: 36rpx;
			font-weight: 900;
			color: rgba(0,0,0,0.87);
			margin-left: 30rpx;
			margin-top: 60rpx;
			line-height: 60rpx;
			.two {
				width: 80rpx;
			}
			.six {
				width: 220rpx;
			}
			.five {
				width: 180rpx;
			}
			.seven {
				width: 260rpx;
			}
			.three {
				width: 120rpx;
			}
			.four {
				width: 150rpx;
			}
			.nine {
				width: 340rpx;
			}
		}
		#bottom {
			margin-top: 30rpx;
		}
	    .bottom-button {
			display: flex;
			margin: 30rpx 0 0 30rpx;
			.left {
				margin-right: 40rpx;
				display: flex;
				image {
					width: 56rpx;
					height: 56rpx;
				}
				view {
					height: 32rpx;
					// width: 66rpx;
					font-size: 33rpx;
					color: #00a862;
					margin-left: 10rpx;
					margin-top: 10rpx;
				}
			}
			.right {
				font-size: 32rpx;
				color: #00a862;
				border: 1px solid #00a862;
				width: 115rpx;
				line-height: 63rpx;
				text-align: center;
				border-radius: 48px;
			}
	}
        .bottom-text {
			font-size: 28rpx;
			color: rgba(0,0,0,0.38);
			display: flex;
			margin: 90rpx 0 0 30rpx;
			view {
				margin-right: 40rpx;
			}
  }
        .error {
			width: 40rpx;
			height: 40rpx;
			position: absolute;
			right: 30rpx;
			top: 30rpx;
		}
}
</style>
