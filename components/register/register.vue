<template>
	<view class="container">
		<!-- 标题文本 -->
		<view class="title">
			使用星巴克App进行注册
		</view>
		<!-- 文本 -->
		<view class="content">
			现在就下载
			<text>星巴克App</text>
			便可直接用手机进行注册、支付、查看消费记录及管理卡片。
		</view>
		<!-- 图片 -->
		<image src="../../static/picture/register.png" mode=""></image>
		<!-- 星巴克app下载标志 -->
		<image class="logo" src="../../static/picture/register-logo.png" mode=""></image>
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
		 position: relative;
		 padding-bottom: 50rpx;
		 .title {
			 margin-top: 70rpx;
			 margin-left: 50rpx;
			 font-size: 40rpx; 
			 letter-spacing: 0.4px;
		 }
		 .content {
			 width: 618rpx;
			 height: 84rpx;
			 font-size: 32rpx;
			 color: rgba(0,0,0,0.87);
			 margin: 40rpx 0 60rpx 50rpx;
			 line-height: 50rpx;
			 letter-spacing: 0.2px;
			 text {
				 color: #00a862;
			 }
		 }
		 image {
			 height: 818rpx;
			 width: 386rpx;
			 margin-left: 182rpx;
		 }
		 .logo {
			 width: 320rpx;
			 height: 104rpx;
			 position: fixed;
			 bottom: 130rpx;
			 right: 30rpx;
		 }
	 }
</style>
