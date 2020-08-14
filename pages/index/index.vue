<template>
	<view class="container">
		<!-- 顶部文字 -->
		<view class="top-text">
			心情惬意，来杯咖啡吧☕
		</view>
		<!-- 轮播图 -->
		<swiper  :autoplay="true" :interval="3000" :duration="1000" circular="">
			<swiper-item>
				<image src="../../static/picture/lunbo1.jpg" mode=""></image>
			</swiper-item>
			<swiper-item>
				<image src="../../static/picture/lunbo2.jpg" mode=""></image>
			</swiper-item>
			<swiper-item>
				<image src="../../static/picture/lunbo3.jpg" mode=""></image>
			</swiper-item>
		</swiper>
		<!-- 广告logo -->
		<view class="adv">
			广告
		</view>
		<!-- 可跳转的链接图 -->
		<view class="a-photo" v-for="(item,index) in photoList" :key='item.index' >
			<!-- <web-view src="https://starbucks.m.tmall.com/"> -->
				<image :src="item.url" mode=""></image>
			<!-- </web-view> -->
		</view>
		<!-- 星享俱乐部 -->
		<view class="club">
			<view class="center-one">星享俱乐部</view>
			<view class="center">开启您的星享之旅，星星越多、会员等级</view>
			<view class="center">越高、好礼越丰富<text class="more">了解更多></text></view>
			<view class="login">
				<view class="login-list">
					注册
				</view>
				<view class="input-list">
					登录
				</view>
			</view>
			<image src="https://www-static.chinacdn.starbucks.com.cn/prod/assets/images/logo-msr-new.svg" mode=""></image>
		</view>
		<!-- 星巴克精选 -->
		<view class="choose">
			<view class="title">
				<view class="top" style="text-align: center;">
					星巴克精选
				</view>
				<view class="bottom" style="text-align: center;">
					在星巴克天猫旗舰店发现更多咖啡心意
				</view>
			</view>
			<view class="cart">
				<view class="cart-list" v-for="(item,index) in cartList" :key='item.index'>
					<image :src="item.imag" mode=""></image>
					<view class="title">{{item.title}}</view>
					<view class="line">{{item.online}}</view>
					<view class="line">{{item.twoline}}</view>
					<view class="bottom">{{item.bottom}}</view>
				</view>
			</view>
		</view>
		<!-- 1912 -->
		<view class="street-1912">
			<view class="title">
				1912派克街|咖啡星讲堂
			</view>
			<view class="content">
				了解更多星巴克咖啡文化
			</view>
			<swiper :autoplay="true" :interval="3000" :duration="1000"   class="cafa" interval="7000" circular=""
			 next-margin="210rpx">
				<swiper-item v-for="(item,index) in cafaList" :key='item.index' class="cafa-list">
					<image :src="item.url" mode=""></image>
					<view class="yellow-label">
						{{item.label}}
					</view>
					<view class="content">
						{{item.title}}
					</view>
				</swiper-item>
			</swiper>
		</view>
		<!-- 公安局 -->
		<view class="bottom-text">
			<image src="../../static/picture/jingchalogo.png" mode=""></image>
			沪公网安备31010402000253号 | 沪ICP备17003747号
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				photoList:[
					{
						url:'../../static/picture/lunbo4.jpg'
					},
					{
						url:'../../static/picture/lunbo5.jpg'
					},
					{
						url:'../../static/picture/lunbo6.jpg'
					}
				],
				cartList:[
					{
						imag:'../../static/picture/cart1.png',
						title:'会员星礼包',
						online:'星享卡新升级',
						twoline:'更多心意好礼',
						bottom:'了解更多>'
					},
					{
						imag:'../../static/picture/cart2.png',
						title:'星礼卡',
						online:'用一份心礼',
						twoline:'让心意相随',
						bottom:'了解更多>'
					},
					{
						imag:'../../static/picture/cart3.png',
						title:'电子产品券',
						online:'心意',
						twoline:'从这一杯开始',
						bottom:'了解更多>'
					},
					{
						imag:'../../static/picture/cart4.png',
						title:'咖啡生活',
						online:'星巴克',
						twoline:'用心制作',
						bottom:'了解更多>'
					}
				],
				cafaList:[
					{
						url:'../../static/picture/cafa1.jpg',
						title:'咖啡的起源与培植',
						label:'咖啡知识'
					},
					{
						url:'../../static/picture/cafa2.jpg',
						title:'咖啡调制',
						label:'咖啡品鉴'
					},
					{
						url:'../../static/picture/cafa3.jpg',
						title:'咖啡烘焙',
						label:'咖啡知识'
					},
					{
						url:'../../static/picture/cafa4.jpg',
						title:'手冲咖啡',
						label:'咖啡品鉴'
					}
				]
			}
		},
		onLoad() {

		},
		methods: {
    
		}
	}
</script>

<style lang="scss" scoped>
	.container {
		margin-bottom: 100rpx;
		.top-text {
			font-weight: 900;
			font-size: 45rpx;
			margin: 40rpx;
		}
		swiper {
			width: 750rpx;
			height: 820rpx;
			swiper-item {
				image {
				  width: 100%;
				  height: 100%;
				}
			}
		}
	    .adv {
			width: 70rpx;
			height: 50rpx;
			font-size: 25rpx;
			line-height: 50rpx;
			text-align: center;
			color: #fff;
			background-color: rgba(0,0,0,0.6);
			position: absolute;
			top: 120rpx;
			right: 10rpx;
		}
		.a-photo {
			width: 750rpx;
			background-color: #f7f7f7;
			padding-bottom: 50rpx;
			image {
				width: 680rpx;
				margin: 40rpx 35rpx 0 35rpx;
				border-radius: 10rpx;
				box-shadow: 0 1px 1px 1px rgba(0,0,0,0.12)
				
			}
		}
	    .club {
			margin-top: 50rpx;
			.center-one {
				font-size: 40rpx;
				text-align: center;
			}
			.center{
				text-align: center;
				font-size: 32rpx;
				margin: 24rpx 0 24rpx 0;
				color: rgba(0,0,0,0.56);
			}
			.login {
				display: flex;
				margin: 60rpx 0 60rpx 239rpx;
				width: 750rpx;
				view {
					border: 1px solid #00A862;
					padding: 12rpx 36rpx;
					border-radius: 106rpx;
					color: #00A862;
					font-size: 30rpx;
					margin-right:20rpx
				}
			}
			image {
				height: 144rpx;
				width: 472rpx;
				margin:0 0 100rpx 139rpx;
			}
		}
	     .choose {
			 background-color: #f7f7f7;
			 .title {
				padding-top: 60rpx;
				 text-align: center;
				 font-size: 32rpx;
				 margin-bottom: 80rpx;
				 view:nth-child(1){
					 font-size: 40rpx;
					 margin-bottom: 40rpx;
				 }
				 view:nth-child(2){
					 color: #6c6c6c;
				 }
			 }
			 .cart {
				 display: flex;
				 flex-wrap: wrap;
				 .cart-list {
					 width: 294rpx;
					 height: 394rpx;
					 border: 1px solid #dedede;
					 border-radius:5px;
					 box-shadow:1px 1px #dedede;
					 margin-left: 50rpx;
					 margin: 100rpx 0 100rpx 50rpx;
					 position: relative;
					 image {
						 width: 160rpx;
						 height: 144rpx;
						 z-index: 2000;
						 display: block;
						 // border:1px solid red;
						 position: relative;
						 top: -72rpx;
						 left: 67rpx;
					 }
					 .title {
						 font-size: 32rpx;
						 margin: -40rpx;
						 text-align: center;
						 color: #212121;
						 padding: 0;
						 margin-bottom: 30rpx;
					 }
					 .line {
						 font-size: 28rpx;
						 text-align: center;
						 color: rgba(0,0,0,0.56);
						 line-height: 50rpx;
					 }
					 .bottom {
						 font-size: 24rpx;
						 text-align: center;
						 color: #d4c191;
						 margin-top: 50rpx;
					 }
				 }
			 }
		 }
		 .street-1912 {
			 letter-spacing: 5rpx;
			 .title {
				 font-size: 40rpx;
				 text-align:center
			 }
			 .content {
				 font-size: 32rpx;
				 text-align:center;
				 margin:40rpx 0 80rpx 0;
				 color: rgba(0,0,0,0.56);
			 }
		 }
		 .cafa {
			 height: 400rpx;
			 .cafa-list {
				 margin-left: 30rpx;
				 width: 508rpx;
				 // height: 200rpx;
				 // border: 1px solid red;
				 image {
					 width: 508rpx;
					 height: 288rpx;
					 border-radius: 5px;
				 }
				 .yellow-label {
					 font-size: 28rpx;
					 background-color: #c2a661;
					 color:#fff;
					 padding: 8rpx 18rpx;
					 width: 130rpx;
					 position: absolute;
					 top: 10rpx;
					 left: 0;
				 }
				 .content {
					 text-align: left;
					 margin-top: 20rpx;
					 margin-left: 20rpx;
					 font-size: 32rpx;
					 color: rgba(0,0,0,0.87);
				 }
			 }
		 }
	}
	 .more{
		color: #c2a661;
		font-size: 32rpx;
		margin-left: 20rpx;
	}
	.bottom-text {
		font-size: 24rpx;
		color: #666;
		text-align: center;
		margin-top: 50rpx;
		margin-bottom: -60rpx;
		image {
			width: 20rpx;
			height: 20rpx;
		}
	}
</style>
