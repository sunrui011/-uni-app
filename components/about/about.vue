<template>
	<view class="container">
		<!-- 第一个图片 -->
		<view class="top-image">
			<image class="logo" src="../../static/about/about.jpeg" mode=""></image>
		     <text>广告</text>
		</view>
		<!-- 绿色背景内容 -->
		<view class="green">
			<!-- 欢迎logo -->
			<view class="welcome-logo">
				<image src="../../static/about/welcome.png" mode=""></image>
			</view>
			<!-- 四个小方框 -->
			<view class="welcome-container">
				<view class="same">
					<image src="../../static/about/welcome-small1.png" mode=""></image>
					<view class="title">
						<view class="top">
							消费积累星星
						</view>
						<view class="medium">
							每累计消费￥50元累计一颗星星
						</view>
						<view class="bottom">
							使用星巴克指定的方式，可享加速积星
						</view>
					</view>
				</view>
				<view class="same">
					<image src="../../static/about/welcome-small2.png" mode=""></image>
					<view class="title">
						积星升级 好礼享不停
					</view>
				</view>
				<view class="same">
					<image src="../../static/about/welcome-small3.png" mode=""></image>
					<view class="title">
						会员专享星星奖励活动
					</view>
				</view>
				<view class="same">
					<image src="../../static/about/welcome-small4.png" mode=""></image>
					<view class="title">
						星星兑换丰富好礼
					</view>
				</view>
			</view>
		    <!-- 详情说明 -->
			<view class="detail">
				详情以
				<text>《星享俱乐部活动的条款和条件》</text>
				的规定为准
			</view>
		</view>
	    <!-- 绿色小箭头 -->
		<view class="green-arrow">
			<image src="../../static/about/arrow-bottom.jpg" mode=""
			  style="width: 750rpx;height: 47.7rpx;"
			></image>
		</view>
	    <!-- 积星升级 -->
		<view class="star">
			<!-- 顶部logo -->
			<image class="logo" src="../../static/about/star-logo.png" mode=""></image>
		    <!-- 三个小块 -->
			<view class="star-container">
				<view class="same">
					<image src="../../static/about/star1.png" mode=""></image>
					<view class="right">
						<view>注册星享俱乐部账户</view>
						<view>即成为
						    <text style="color: #000; font-weight: 900;">银星级</text>
						会员</view>
						<view>可开始消费积星星</view>
					</view>
				</view>
				<view class="same">
					<image src="../../static/about/star2.png" mode=""></image>
					<view class="right" style="padding-top: 15rpx;">
						<view>累积4颗星星</view>
						<view>升级至
						  <text style="color: #00a862;font-weight: 900;">玉星级</text>
						会员</view>
					</view>
				</view>
				<view class="same">
					<image src="../../static/about/star3.png" mode=""></image>
					<view class="right">
						<view>玉星级</view>
						<view>再累积16颗星星</view>
						<view>升级至
						  <text style="color: #c2a661;font-weight: 900;">金星级</text> 
						会员</view>
					</view>
				</view>
			</view>
		    <!-- 详情小字 -->
			<view class="star-detail">
				详情以
				<text>《星享俱乐部活动的条款和条件》</text>
				的规定为准
			</view>
		</view>
		<!-- 底部 image-->
		<image class="star-bottom" src="../../static/about/star-bottom.jpg" mode=""></image>
	    <!-- 各等级会员权益 -->
		<view class="member">
			<!-- logo照片 -->
			<image class="member-logo" src="../../static/about/member-logo.png" mode=""></image>
		    <!-- 三块内容 -->
			<view class="member-content">
				<view class="same">
					<image src="../../static/about/member1.png" mode=""></image>
					<view class="block">
						<view class="list">
							<view class="circle"></view>
							<text>购买绑定会员星礼包可直通玉星级</text>
						</view>
						<view class="list">
							<view class="circle"></view>
							<text>各类奖励星星活动</text>
						</view>
					</view>
				</view>
				<view class="same">
					<image src="../../static/about/member2.png" mode=""></image>
					<view class="block" style="margin-top: -80rpx;">
						<view class="list">
							<view class="circle" style="background-color: #008a62;"></view>
							<text>玉星晋级饮品券</text>
						</view>
						<view class="list">
							<view class="circle" style="background-color: #008a62;"></view>
							<text>金星在望饮品券</text>
						</view>
						<view class="list">
							<view class="circle" style="background-color: #008a62;"></view>
							<text>生日饮品券</text>
						</view>
						<view class="list">
							<view class="circle" style="background-color: #008a62;"></view>
							<text>永享玉星级保级</text>
						</view>
						<view class="list">
							<view class="circle" style="background-color: #008a62;"></view>
							<text>各类奖励星星活动</text>
						</view>
					</view>
				</view>
				<view class="same" style="margin-top: 30rpx;">
					<image src="../../static/about/member3.png" mode=""></image>
					<view class="block" style="margin-top: -80rpx;">
						<view class="list">
							<view class="circle" style="background-color: #d9b659;"></view>
							<text>金星晋级饮品券</text>
						</view>
						<view class="list">
							<view class="circle" style="background-color: #d9b659;"></view>
							<text>周年庆饮品券</text>
						</view>
						<view class="list">
							<view class="circle" style="background-color: #d9b659;"></view>
							<text>生日饮品券</text>
						</view>
						<view class="list">
							<view class="circle" style="background-color: #d9b659;"></view>
							<text>永享玉星级保级</text>
						</view>
						<view class="list">
							<view class="circle" style="background-color: #d9b659;"></view>
							<text>好礼星星兑换</text>
						</view>
						<view class="list">
							<view class="circle" style="background-color: #d9b659;"></view>
							<text>各类奖励星星活动</text>
						</view>
					</view>
				</view>
			</view>
			<!-- member详情 -->
			<view class="member-detail">
				详情以
				<text>《星享俱乐部活动的条款和条件》</text>
				的规定为准
			</view>
			<!-- 会员下的分割图 -->
			<view class="member-bottom-logo">
				<image src="../../static/about/member-bottom-logo.png" mode=""></image>
			</view>
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
	   margin-bottom: 100rpx;
	   margin-top: 25rpx;
	   .top-image{
		   position: relative;
		   .logo {
		   		 width: 750rpx;
		   		 height: 1040rpx;
		   }
		   text {
			   width: 80rpx;
			   height: 44rpx;
			   background-color: #000;
			   color: #fff;
			   font-size: 24rpx;
			   padding: 5rpx 5rpx;
			   position: absolute;
			   text-align: center;
			   line-height: 44rpx;
			   top: 20rpx;
			   right: 20rpx;
			   opacity: 0.6;
			   border-radius: 2px;
		   }
	   }
	   .green {
		   position: relative;
		   margin-top: -10rpx;
		   width: 750rpx;
		   height: 786rpx;
		   background-color: #023529;
		   padding: 96rpx 0 144rpx 0;
		   .welcome-logo {
			   image {
				   width: 549rpx;
				   height: 56rpx;
				   margin-left: 100.5rpx;
			   }
		   }
		   .welcome-container {
			   color: #fff;
			   display: flex;
			   flex-wrap: wrap;
			   margin-top: 40rpx;
			   // margin-right: 10rpx;
			   .same {
				   width: 311rpx;
				   height: 340rpx;
				   margin: 30rpx 10rpx 30rpx 50rpx;
				   image {
					   width: 160rpx;
					   height: 160rpx;
				   }
				   .title {
					   font-size: 28rpx;
					   .medium{
						   font-size: 19.2rpx;
						   margin-top: 10rpx;
						   width: 270rpx;
						   text-align: center;
					   }
					   .bottom {
						   font-size: 19.2rpx;
						   width: 270rpx;
						   text-align: center;
					   }
				   }
			   }
		   }
	       .detail {
			   font-size: 20rpx;
			   width: 675.4rpx;
			   height: 20.8rpx;
			   color: #fff;
			   margin-left: 140rpx;
			   position: absolute;
			   bottom: 40rpx;
			   text {
				   color: #008a62;
			   }
		   }
	   }
       .star {
		   background-color: #ebf3f5;
		   width: 750rpx;
		   height: 950rpx;
		   margin-top: -10rpx;
		   position: relative;
		   .logo {
			   width: 686rpx;
			   height: 52rpx;
			   margin: 60rpx 0 0 30rpx;
		   }
		   .star-container {
			   .same {
				   display: flex;
				   margin-left: 120rpx;
				   margin-top: 100rpx;
				   image {
					   width: 148rpx;
					   height: 104rpx;
					   padding-right: 50rpx;
				   }
				   .right {
					   view{
						   font-size: 26rpx;
						   color: rgba(0,0,0,0.87);
					   }
				   }
			   }
		   }
	       .star-detail {
			   font-size: 20rpx;
			   position: absolute;
			   bottom: 70rpx;
			   left: 150rpx;
			   text {
				   color: #008a62;
			   }
		   }
	   }
       .star-bottom {
       			   height: 60rpx;
       			   width: 750rpx;
       }
       .member {
		   width: 750rpx;
		   height: 1000rpx;
		   .member-logo {
			   width: 453rpx;
			   height: 56.6rpx;
			   margin: 30rpx 0 0 130rpx;
		   }
		   .member-content {
			   margin: 30rpx 0 0 60rpx;
			   .same {
				   height: 300rpx;
				   display: flex;
				   image {
					   width: 140rpx;
					   height: 130rpx;
					   margin-right: 60rpx;
				   }
				   .block {
					   .list {
						   display: flex;
						   margin: 20rpx;
						   .circle {
							   width: 12rpx;
							   height: 12rpx;
							   background-color: #ddd;
							   border-radius: 50%;
							   margin-top: 12rpx;
							   margin-right: 10rpx;
						   }
						   text {
							  font-size: 26rpx; 
						   }
					   }
				   }
			   }
		   }
	       .member-detail {
			   font-size: 20rpx;
			   margin: 50rpx 0 0 150rpx;
			   padding-bottom: 50rpx;
			   text {
				   color: #008a62;
			   }
		   }
	   }
       .member-bottom-logo {
		   // position: absolute;
		   margin-bottom: 100rpx;
		   top: 0;
		   image {
			   width: 750rpx;
			   height: 46rpx;
		   }
	   }
   }
</style>
