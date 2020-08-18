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
	    <!-- 用星星兑换你喜爱的产品 -->
		<view class="exchange-container">
			<!-- 顶部logo -->
			<image class="exchange-top-logo" src="../../static/about/exchange-top-logo.png" mode=""></image>
		    <!-- 一行文字 -->
			<view class="text">快来升级金星会员，各种兑换好礼等你</view>
			<!-- 五个小块 -->
			<view class="exchange-block">
				<view class="small-block" v-for="(item,index) in exchangeList" :key='item.index'>
					<image :src="item.url" mode=""></image>
				    <view class="block-text">
				    	<text>{{item.text}}</text>
						<image class="block-text-star" src="https://www.starbucks.com.cn/assets/icons/icon-star-gold.svg" mode=""></image>
				    </view>
				</view>
			</view>
		    <!-- 切换卡片 -->
		    <view class="exchange-cart">
		    	<!-- 标题 -->
				<view class="title">
					定制你爱的那杯
				</view>
				<!-- 内容文字 -->
				<view class="exchange-content">
					升杯、添加浓缩咖啡、糖浆等付费客制化
				</view>
				<!-- 兑换规则 -->
				<view class="exchange-rule">
					兑换规则>
				</view>
				<!-- 图片 -->
				<image class="exchange-rule-logo" src="../../static/about/exchange-rule.png" mode=""></image>
		        <image class="exchange-bottom-image" src="../../static/about/exchange-bottom-picture.jpg" mode=""></image>
			</view>
		</view>
	    <!-- 星享俱乐部会员星礼包 -->
	    <view class="gift-container">
	    	<image class="gift-logo" src="../../static/about/gift-logo.png" mode=""></image>
	        <image class="gift-black-logo" src="../../static/about/gift-black-logo.png" mode=""></image>
		    <image class="gift-discout" src="../../static/about/gift-discout.png" mode=""></image>
		    <!-- 文本区域 -->
			<view class="gift-text">
				<view class="gift-title">
					选购会员星礼包，丰富好礼随心享:
				</view>
				<!-- 中字 -->
				<view class="title-medium">
					<view class="same">
						<view class="circle"></view>
						<text>6张电子好礼券*,适用多种商品种类</text>
					</view>
					<view class="same">
						<view class="circle"></view>
						<text>附赠一张精美星礼卡**,可绑定至星巴克中国App内充值并支付</text>
					</view>
					<view class="same">
						<view class="circle"></view>
						<text>银星级会员初次将会员星礼包成功绑定至账户后，即可升级成为玉星级会员</text>
					</view>
				</view>
			    <!-- 小字 -->
				<view class="title-small">
					<view class="same">
						* 每份券将在添加至您的星享俱乐部账户的当天生效，有效期为90天。
					</view>
					<view class="same">
						** 附赠星礼卡的初始余额为0元
					</view>
				</view>
			    <!-- 详情小字 -->
				<view class="gift-detail">
					详情以
					<text>《星享俱乐部活动的条款和条件》</text>
					的规定为准
				</view>
			    <!-- 箭头向下的图片 -->
				<image class="gift-bottom-arrow" src="../../static/about/gift-bottom-arrow.jpg" mode=""></image>
			</view>
		</view>
	    <!-- 多种获取星星途径 -->
		<view class="star-methods">
			<!-- 顶部logo -->
			<image  class="star-methods-logo" src="../../static/about/star-methods-logo.png" mode=""></image>
		    <!-- 五块小内容 -->
			<view class="methods-container">
				<!-- 上边三 -->
				<view class="methods-top-three">
					<view class="top-list" v-for="(item,index) in methodstopList" :key='item.index'>
						<image :src="item.url" mode=""></image>
						<view class="title">
							{{item.title}}
						</view>
						<view class="content">
							{{item.content}}
						</view>
					</view>
				</view>
				<!-- 下边两个 -->
				<view class="methods-bottom-two">
					<view class="top-list" v-for="(item,index) in methodsbottomList" :key='item.index'>
						<image :src="item.url" mode=""></image>
						<view class="title">
							{{item.title}}
						</view>
						<view class="content">
							{{item.content}}
						</view>
					</view>
				</view>
			</view>
		    <!-- 详情 -->
			<view class="methods-detail">
				详情以
				<text>《星享俱乐部活动的条款和条件》</text>
				的规定为准
			</view>
			<!-- 下方箭头图片 -->
			<image class="methods-arrow" src="../../static/about/methods-bottom-arrow.jpg" mode=""></image>
	</view>
	<!-- 轻松注册星享俱乐部会员 -->
	<view class="club-member-container">
		<!-- 顶部logo -->
		<image class="club-top-logo" src="../../static/about/club-member-logo.png" mode=""></image>
	    <!-- 两块文字 -->
		<view class="lists">
			<view class="list" v-for="(item,index) in clubmemberList" :key='item.index'>
				<!-- title -->
				<view class="title">
					{{item.title}}
				</view>
				<!-- oneLine -->
				<view class="text">{{item.oneLine}}</view>
				<!-- twoLine -->
				<view class="text">{{item.twoLine}}</view>
				<!-- 按钮 -->
				<view class="button">
					{{item.logo}}
				</view>
			</view>
		</view>
	    <!-- 详情 -->
		<view class="club-detail">
			详情以
			<text>《星享俱乐部活动的条款和条件》</text>
			的规则为准
		</view>
	    <!-- 中间的横线 -->
		<view class="line"></view>
	  
	</view>
	<!-- 下边的箭头 -->
	<image class="club-arrow-bottom" src="../../static/about/club-bottom-arrow.jpg" mode=""></image>
	<!-- 星享俱乐部常见问题 -->
	<view class="trouble-container">
		<image class="troble-logo" src="../../static/about/trouble-logo.png" mode=""></image>
		<!-- 折叠框 -->
		<uni-collapse @change="change">
		    <uni-collapse-item  title="加入星享俱乐部" open="true" style="background-color: #fff; font-size: 32rpx;">
				    <!-- 01 -->
		            <view  style="padding: 30rpx; font-size: 28rpx; line-height: 50rpx; background-color: #fff; width: 560rpx;" class="item" id="item1" v-for="(item,index) in trouble1" :key='item.index'>
					   <text style="margin: 40rpx 0 0 40rpx;">{{item.text}}</text>
					   <view class="item-text" style="margin: 60rpx 0 0 50rpx; line-height: 50rpx;">
					   	 {{item.content}}
					   </view>
				    </view>
		    </uni-collapse-item>
			<!-- 02 -->
			<uni-collapse-item  title="会员等级和好礼" open="true" style="background-color: #ebf3f5; font-size: 32rpx;">
				   <!-- 02 -->
				   <view  style="padding: 30rpx; font-size: 28rpx; line-height: 50rpx; background-color: #ebf3f5; width: 560rpx;" class="item" id="item1" v-for="(item,index) in trouble2" :key='item.index'>
				      <text style="margin: 40rpx 0 0 40rpx;">{{item.text}}</text>
				      <view class="item-text" style="margin: 60rpx 0 0 50rpx; line-height: 50rpx;">
				      	 {{item.content}}
				      </view>
					  <view style="margin: 60rpx 0 0 50rpx; line-height: 50rpx;">
					  	{{item.bottom}}
					  </view>
				   </view>
			</uni-collapse-item>
			<!-- 03 -->
			<uni-collapse-item  title="会员服务" open="true" style="padding-bottom: 50rpx;">
				    <!-- 01 -->
			        <view style="padding: 30rpx;">
					   
				    </view>
			</uni-collapse-item>
		</uni-collapse>
	    <!-- 绿板块 -->
		<view class="green-container">
			<!-- 上一行 -->
			<text>详情以《星享俱乐部的条款和条件》的规定为准</text>
			<!-- 中间行 -->
			<view class="medium">
				@2020 Starbucks Corporation.All rights reserved.
			</view>
			<!-- 下边行 -->
			<view class="bottom">
				<image src="../../static/about/jingcha-logo.png" mode=""></image>
				<view class="text-bottom">
					沪公网安备 31010402000253号 沪ICP备17003747号
				</view>
			</view>
		</view>
	</view>
</view>
</template>

<script>
	import uniCollapse from '@/components/uni-collapse/uni-collapse.vue'
	import uniCollapseItem from '@/components/uni-collapse-item/uni-collapse-item.vue'
	export default {
		data() {
			return {
				exchangeList:[
					{
						url:'../../static/about/exchange1.png',
						text:'1'
					},
					{
						url:'../../static/about/exchange2.png',
						text:'9'
					},
					{
						url:'../../static/about/exchange3.png',
						text:'12'
					},
					{
						url:'../../static/about/exchange4.png',
						text:'15'
					},
					{
						url:'../../static/about/exchange5.png',
						text:'25'
					}
				],
			    methodstopList:[
					{
						url:'../../static/about/methods1.png',
						title:'星巴克门店'
					},
					{
						url:'../../static/about/methods2.png',
						title:'专星送TM',
						content:'(仅限已开通门店)'
					},
					{
						url:'../../static/about/methods3.png',
						title:'啡快',
						content:'(仅限已开通门店)'
					}
				],
				methodsbottomList:[
					{
							url:'../../static/about/methods4.png',
							title:'星巴克天猫',
							content:'会员旗舰店'
					},
					{
						url:'../../static/about/methods5.png',
						title:'星星奖励',
						content:'活动'
					}
				],
				clubmemberList:[
					{
						title:'现在就来加入星享俱乐部',
						oneLine:'轻松注册,立即开启',
						twoLine:'您的全新星享旅行,好礼享不停',
						logo:'立即注册'
					},
					{
						title:'已是星享俱乐部的会员',
						oneLine:'您可快速绑定会员星礼包,',
						twoLine:'专享加速积星,丰富好礼等你',
						logo:'立即登录'
					}
				],
			    trouble1:[
					{
						text:'1.1   什么是星享俱乐部?',
						content:'星享俱乐部是星巴克推出的顾客忠诚计划。您可以通过注册星享俱乐部账户成为星享俱乐部会员,并通过消费积累"星星"、享受会员权益。'
					},
					{
						text:'1.2   如何加入星享俱乐?',
						content:'星享俱乐部是星巴克推出的顾客忠诚计划。您可以通过注册星享俱乐部账户成为星享俱乐部会员,并通过消费积累"星星"、享受会员权益。'
					},
					{
						text:'1.3   通过星巴克App和通过其他渠道加入星享俱乐部有什么不同?',
						content:'星享俱乐部是星巴克推出的顾客忠诚计划。您可以通过注册星享俱乐部账户成为星享俱乐部会员,并通过消费积累"星星"、享受会员权益。'
					},
					{
						text:'1.4   如何登陆和使用我的星享俱乐部账户?',
						content:'星享俱乐部是星巴克推出的顾客忠诚计划。您可以通过注册星享俱乐部账户成为星享俱乐部会员,并通过消费积累"星星"、享受会员权益。'
					}
				],
			    trouble2:[
				   {
					   text:'2.1   星星有什么用？',
					   content:'在成功注册星享俱乐部帐户后，您每次在参加星享俱乐部活动的星巴克门店或通过星巴克App以及星巴克不时指定的其他渠道购买产品（不包括会员星礼包、星礼卡等产品，详见本问答第2.4问，以下简称"除外商品"时,可以在您的星享俱乐部帐户中累积星星。',
					   bottom:'星星分为等级星星，基础好礼星星和奖励好礼星星。“ 等级星星 ”是指用于确定会员等级的积分。当等级星星累积达到一定的数量时，您将从银星级会员升级为玉星级会员或者从玉星级会员升级为金星级会员，并且可以享受该等级所对应的会员礼遇。"基础好礼星星"和"奖励好礼星星",合称为“好礼星星”，是指金星级会员专享的可用于兑换星巴克不时指定的产品和参与或兑换星巴克不时指定的权益的积分，奖励好礼星星的有效期短于基础好礼星星。'
				   }
				]
			};
		},
		components:{
			uniCollapse,
			uniCollapseItem
		}
	}
</script>

<style lang="scss">
   .container {
	   margin-bottom: 100rpx;
	   margin-top: 25rpx;
	   position: relative;
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
       .exchange-container {
		   // border: 1px solid red;
		   position: absolute;
		   top: 4430rpx;
		   padding-bottom: 200rpx;
		   .exchange-top-logo {
			   width: 686rpx;
			   height: 48.6rpx;
			   margin-left: 40rpx;
		   }
		   .text {
			   font-size: 36rpx;
			   color: rgba(0,0,0,0.56);
			   margin: 40rpx 0 0 60rpx;
		   }
	       .exchange-block {
			   margin: 100rpx 0rpx 0 60rpx;
			   display: flex;
			   .small-block {
				   flex: 1;
				   image {
					   width: 68rpx;
					   height: 74rpx;
				   }
				   .block-text {
					   text {
						   font-size: 36rpx;
					   }
					   .block-text-star {
						   width: 28rpx;
						   height: 28rpx;
						   margin-left: 10rpx;
					   }
					   
				   }
			   }
		   }
	   }
       .exchange-cart {
		   width: 750rpx;
		   height: 366rpx;
		   margin-top: 40rpx;
		   background-color: #ebf3f5;
		   border-top: 3px solid #ececec;
		   position: relative;
		   .title {
			   width: 260rpx;
			   height: 44rpx;
			   color: #32433d;
			   font-size: 36rpx;
			   font-weight: 900;
			   margin-left:60rpx;
			   padding-top: 90rpx;
		   }
		   .exchange-content {
			   font-size: 28rpx;
			   width: 403rpx;
			   height: 77rpx;
			   color: rgba(0,0,0,0.56);
			   letter-spacing: 0.3px;
			   margin: 40rpx 0 0 60rpx;
	   }
	   .exchange-rule {
		   color: #008a62;
		   font-size: 28rpx;
		   width: 136rpx;
		   height: 51rpx;
		   margin: 40rpx 0 0 60rpx;
	   }
	   .exchange-rule-logo {
		   width: 200rpx;
		   height: 200rpx;
		   position: absolute;
		   right: 20rpx;
		   bottom: 10rpx;
	   }
	   .exchange-bottom-image {
		   width: 750rpx;
		   height: 46rpx;
	   }
   }
}
.gift-container {
	position: absolute;
	top: 5224rpx;
   	width: 750rpx;
	padding-bottom: 100rpx;
   	background-color: #fff;
	.gift-logo {
		width: 590rpx;
		height: 55rpx;
		margin: 50rpx 0 0 80rpx;
	}
	.gift-black-logo {
		width: 420rpx;
		height: 290rpx;
		margin: 60rpx 0 0 150rpx;
	}
	.gift-discout {
		width: 560rpx;
		height: 352rpx;
		margin: 50rpx 0 0 100rpx;
	}
    .gift-text {
		.gift-title {
			font-size: 32rpx;
			width: 586rpx;
			height: 45rpx;
			color: #000;
			font-weight: 900;
			margin: 60rpx 0 0 120rpx;
		}
		.title-medium {
			margin: 30rpx 0 0 100rpx;
			.same {
				display: flex;
				margin-bottom: 20rpx;
				.circle {
					width: 10rpx;
					height: 10rpx;
					border-radius: 50%;
					background-color: #c2a661;
					margin-top: 15rpx;
				}
				text {
					font-size: 26rpx;
					width: 606rpx;
					line-height: 40rpx;
					margin-left: 20rpx;
				}
			}
		}
	    .title-small {
			margin: 50rpx 0 0 130rpx;
			.same {
				font-size: 20rpx;
				width: 580rpx;
				height: 54rpx;
				letter-spacing: 0.2px;
				margin-bottom: 10rpx;
				line-height: 30rpx;
				
			}
		}
	    .gift-detail {
			font-size: 20rpx;
			width: 675.4rpx;
			height: 28rpx;
			margin: 50rpx 0 60rpx 140rpx;
			text {
				color: #008a62;
			}
	}
        .gift-bottom-arrow {
			width: 750rpx;
			height: 46rpx;
	}
  }
}
.star-methods {
	padding-bottom: 100rpx;
	position: absolute;
	top: 6835rpx;
	background-color: #023529;
	width: 750rpx;
	.star-methods-logo {
		width: 508rpx;
		height: 56rpx;
		margin: 80rpx 0 0 120rpx;
	}
	.methods-container {
		margin-top: 60rpx;
		.methods-top-three {
			display: flex;
			margin-left: 70rpx;
			.top-list {
				flex: 1;
				image {
					width: 144rpx;
					height: 72rpx;
				}
				.title {
					font-size: 26rpx;
					color: #fff;
					margin-top: 30rpx;
					width: 150rpx;
					text-align: center;
					// height: 70rpx;
				}
				.content {
					font-size: 20rpx;
					color: #fff;
					margin-top: 10rpx;
				}
			}
		}
		.methods-bottom-two {
			display: flex;
			margin-left: 170rpx;
			margin-top: 150rpx;
			.top-list {
				flex: 1;
				image {
					width: 128rpx;
					height: 102rpx;
				}
				.title {
					font-size: 26rpx;
					color: #fff;
					margin-top: 30rpx;
				}
				.content {
					font-size: 26rpx;
					color: #fff;
					margin-top: 10rpx;
					width: 130rpx;
					text-align: center;
				}
			}
		}
	}
    .methods-detail {
		font-size: 20rpx;
		width: 676rpx;
		height: 28rpx;
		color: #fff;
		margin: 100rpx 0 0 140rpx;
		text {
			color: #00a862;
		}
	}
}
.methods-arrow {
		width: 750rpx;
		height: 60rpx;
		margin-top: 100rpx;
		margin-bottom: 50rpx;
		position: absolute;
		top: 885rpx;
	}
.club-member-container {
	background-color: #ebf3f5;
	margin-bottom: 200rpx;
	width: 750rpx;
	// height: 1500rpx;
	position: absolute;
	top: 7870rpx;
	.club-top-logo {
		width: 646rpx;
		height: 56rpx;
		margin: 100rpx 0 0 50rpx;
	}
	.lists {
		margin-top: 50rpx;
		.list {
			margin-bottom: 130rpx;
			.title {
				font-size: 32rpx;
				width: 590rpx;
				height: 44.8rpx;
				text-align: center;
				margin-bottom: 30rpx;
				margin-left: 60rpx;
			}
			.text {
				width: 590rpx;
				height: 50rpx;
				font-size: 26rpx;
				color: rgba(0,0,0,0.87);
				text-align: center;
				margin-left: 50rpx;
				letter-spacing: 1px;
			}
			.button {
				color: #fff;
				background-color: #15767c;
				font-size: 28rpx;
				width: 203rpx;
				height: 51rpx;
				line-height: 51rpx;
				text-align: center;
				border-radius: 48px;
				margin: 30rpx 0 50rpx 250rpx;
			}
		}
	}
    .club-detail {
		font-size: 20rpx;
		height: 20rpx;
		width: 470rpx;
		margin: -40rpx 0 0 130rpx;
		padding-bottom: 40rpx;
		text {
			color: #00a862;
		}
	}
    .line {
		width: 527rpx;
		height: 2rpx;
		background-color: rgba(0,0,0,0.56);
		position: absolute;
		top: 530rpx;
		left: 100rpx;
	}
	
}
.club-arrow-bottom {
		width: 750rpx;
		height: 47rpx;
		margin-top: 30rpx;
		position: absolute;
		top: 8840rpx;
		margin-bottom: 100rpx;
}
.trouble-container {
	width: 750rpx;
	position: absolute;
	top: 9000rpx;
	.troble-logo {
		width: 563rpx;
		height: 56rpx;
		margin: 0 0 0 100rpx;
	}
}
.green-container {
	padding-top: 50rpx;
	width: 750rpx;
	height: 405rpx;
	background-color: #013529;
	margin-top: 0rpx;
	text {
		width: 334rpx;
		height: 22rpx;
		color: #fff;
		font-size: 24rpx;
		margin-left: 120rpx;
	}
	.medium {
		width: 478rpx;
		height: 56rpx;
		color: #fff;
		font-size: 24rpx;
		margin: 30rpx 0 0 130rpx;
		letter-spacing: 1px;
		text-align: center;
	}
	.bottom {
		display: flex;
		margin: 40rpx 0 0 100rpx;
		image {
			width: 18rpx;
			height: 18rpx;
			margin-right: 10rpx;
			margin-top: 6rpx;
		}
		.text-bottom {
			width: 524rpx;
			height: 60rpx;
			color: #fff;
			font-size: 24rpx;
		}
	}
}
</style>
