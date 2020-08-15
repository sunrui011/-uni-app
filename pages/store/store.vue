<template>
	<view class="container">
		<!-- 地图之上 -->
		<view class="top">
			<!-- 陕西西安 -->
			<view class="local">
				   <image src="https://www-static.chinacdn.starbucks.com.cn/prod/assets/icons/icon-locator-green.svg" mode=""></image>
				   <view>陕西 西安 新城</view>
				   <image class="arrow" src="https://www-static.chinacdn.starbucks.com.cn/prod/assets/icons/icon-locator-arrow.svg" mode=""></image>
			</view>
			<!-- 输入地址 -->
			<view class="address">
				<form>
					<input type="text" value="" placeholder="输入地址查找门店">
				</form>
				<image src="https://www.starbucks.com.cn/assets/icons/icon-search.svg" mode=""></image>
			    <text>筛选</text>
			</view>
		</view>
		<!-- 地图 --> 
		<map class="map" :latitude="latitude" :longitude="longitude" :scale="scale" :markers="marker">
            <view class="sign">
            	<view class="add">
            		+
            	</view>
				<view class="add" style="font-size: 80rpx;">
					-
				</view>
            </view>
			<view class="see">
				放大缩小地图来查看更多门店
			</view>
			<view class="small-title">
				@ 2020 AutoNAvi - GS(2019)6379号
			</view>
	    </map>
		<!-- 列表 -->
		<view class="store">
			<view class="store-list" v-for="(item,index) in dataList" :key='item.index'>
				<!-- 第一行 -->
				<view class="oneline">
					<text class="title">
						{{item.title}}
					</text>
					<image class="image1" src="https://www.starbucks.com.cn/assets/icons/delivery.png" mode=""></image>
				    <image class="image2" src="https://www.starbucks.com.cn/assets/icons/icon-mop.svg" mode=""></image>
				</view>
				<!-- 第二行 -->
				<view class="twoline">
					<!-- <image src="https://www.starbucks.com.cn/assets/icons/icon-pin-solid-grey.svg" mode=""></image> -->
					<view class="content">
						{{item.content}}
					</view>
				</view>
				<!-- 第三行 -->
				<view class="num">
					{{item.num}}
				</view>
				<!-- 第四行 -->
				<view class="m">
					{{item.long}}
				</view>
				<image class="map" src="https://www.starbucks.com.cn/assets/icons/icon-pin-solid-grey.svg" mode=""></image>
			    <view class="map-num">
			    	{{item.number}}
			    </view>
				<image class="rightlogo" src="https://www.starbucks.com.cn/assets/icons/icon-info-green.svg" mode=""></image>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				latitude:'34.266208',
				longitude:'108.732804',
				scale:12,
				marker:[
					{
						latitude:'34.266208',
						longitude:'108.732804',
						iconPath:'https://www.starbucks.com.cn/assets/icons/icon-pin-solid-grey.svg'
					}
				],
				dataList:[
					{
						title:'西安北大街店',
						content:'西安市 莲湖区 新世界百货一层 北大街',
						num:'88号',
						long:'145m',
						number:1
					},
					{
						title:'西安钟楼店',
						content:'西安市 西大街1号钟鼓楼广场',
						num:'1号',
						long:'367m',
						number:2,
					},
					{
						title:'西安宏府大厦店',
						content:'西安市 西安市莲湖区北大街11号宏府大',
						num:'厦零售区地上二层2-21单元',
						long:'466m',
						number:3
					},
					{
						title:'西安开元店',
						content:'西安市 解放广场6号开源商城负一楼',
						num:'负1号',
						long:'494m',
						number:4
					},
					{
						title:'西安骡马市店',
						content:'西安市 东大街骡马市1号兴正元百货一楼',
						num:'1号',
						long:'522m',
						number:5
					},
					{
						title:'西安群光广场店',
						content:'西安市 新城区 群光广场一层1D03单元',
						num:'东大街301号',
						long:'677m',
						number:6
					},
					{
						title:'西安南大街中大国际店',
						content:'西安市 西安市碑林区南大街30号中大国',
						num:'际一楼',
						long:'1.0km',
						number:7
					},
					{
						title:'西安伟业大厦店',
						content:'西安市 碑林区 伟业大厦一层1-8号单元',
						num:'南广济街69号',
						long:'1.2km',
						number:8
					},
					{
						title:'西安苏宁生活广场店',
						content:'西安市 新城区 苏宁生活广场一层 解放',
						num:'路186号',
						long:'1.4km',
						number:9
					},
				]
			};
		}
	}
</script>

<style lang="scss" scoped>
     .container {
		 .top {
			 margin-top: 40rpx;
			 margin-left: 30rpx;
			 .local {
				 display: flex;
					 image {
						 width: 28rpx;
						 height: 36rpx;
						 margin-right: 10rpx;
					 }
				     view {
					     font-size: 24rpx;
				     }
					 .arrow {
						 width: 20rpx;
						 height: 16rpx;
						 margin-left: 12rpx;
						 margin-top: 10rpx;
					 }
			 }
		     .address {
				 display: flex;
				 margin-top: 20rpx;
				 form {
					 input {
						 border-bottom: 1px solid #e0e0e0;
						 padding: 10rpx;
						 width: 550rpx;
					 }
				 }
				 image{
				 	 width: 44rpx;
				 	 height: 44rpx;
					 margin: 15rpx 0 0 -50rpx;
				 }
				text{
					font-size: 34rpx;
					color: #00a862;
					margin: 15rpx 0 0 20rpx;
				}
			 }
		 }
	     .map {
			 width: 750rpx;
			 height: 600rpx;
			 .sign {
				 position: absolute;
				 bottom: 60rpx;
				 right: 20rpx;
				 .add{
					 border: 1px solid #ddd;
					 width: 70rpx;
					 height: 90rpx;
					 color: #666;
					 text-align: center;
					 line-height: 90rpx;
					 background-color: rgba(255,255,255,0.9);
					 font-size: 52rpx;
					 border-radius: 3px;
				 }
			 }
			 .see {
				 width: 404rpx;
				 height: 74rpx;
				 line-height: 74rpx;
				 text-align: center;
				 font-size: 26rpx;
				 color: rgba(0,0,0,0.87);
				 border: 1px solid #fff;
				 background-color: #fff;
				 border-radius: 5px;
				 position: absolute;
				 right: 140rpx;
				 bottom: 65rpx;
			 }
			 .small-title {
				 color: rgba(0,0,0,0.87);
				 font-size: 22rpx;
				 height: 38rpx;
				 width: 400rpx;
				 position: absolute;
				 right:200rpx;
				 bottom: -10rpx;
			 }
		 }
	 }
      .store {
		  .store-list {
			  border-bottom: 1px solid #ddd;
			  padding: 40rpx 0;
			  position: relative;
			  .oneline {
				  margin-left: 150rpx;
				  .title {
					  font-size: 30rpx;
					  font-weight: 900;
				  }
				  .image1 {
					 width: 56rpx;
					 height: 40rpx;
					 margin: 0 10rpx 0 20rpx;
				  }
				  .image2 {
					  width: 80rpx;
					  height: 72rpx;
					  position: absolute;
					  top: 22rpx;
				  }
			  }
			  .twoline {
				  display: flex;
				  margin-top: 20rpx;
				  margin-left: 150rpx;
				 
				  .content {
					  font-size: 28rpx;
					  color: rgba(0,0,0,0.56);
				  }
			  }
			  .num {
				  font-size: 28rpx;
				  color: rgba(0,0,0,0.56);
				  margin-left: 150rpx;
				  margin-top: 20rpx;
			  }
			  .m {
				  font-size: 28rpx;
				  color: rgba(0,0,0,0.66);
				  margin-left: 150rpx;
				  margin-top: 20rpx;
			  }
		  }
		  .map {
		  		  width: 50rpx;
		  		  height: 58rpx;
				  position: absolute;
				  top: 100rpx;
				  left: 90rpx;
		  }
		  .map-num {
			  color: #fff;
			  font-size: 24rpx;
			  position: absolute;
			  top: 105rpx;
			  left: 106rpx;
		  }
		  .rightlogo {
			  width: 44rpx;
			  height: 44rpx;
			  position: absolute;
			  top: 120rpx;
			  right: -60rpx;
		  }
	  }
</style>
