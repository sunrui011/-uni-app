<template>
	<view class="container">
		<!-- 菜单两字 -->
		<view class="top-menu">菜单</view>
		<!-- 横条选择 -->
		<view class="selected-line">
			<view style="font-weight: 900;">季度精选</view>
			<view>饮料</view>
			<view>美食</view>
			<view>咖啡产品</view>
			<view>商品</view>
		</view>
		<!-- 一条横线 -->
		<view class="line"></view>
		<!-- 1图与字 -->	
		<view id="one" class="same">
			<image src="../../static/menu/sessionSelect/big1.jpg" mode=""></image>
		    <view class="one-text">
		    	<text class="title">茶做的云 轻轻放纵</text>
				<view class="text-content">
					星巴克茶云乌龙系列清新上市。<br/>
					精选特级高山乌龙，新鲜调制甘醇乌龙茶汤，<br/>
					千次搅打成云，茶云绵密细腻，<br/>
					零脂*不含奶，清爽宜人。<br/>
					细密茶云包裹甘甜水果果汁与甜脆果丁，<br/>
					茶韵果香在味蕾缓缓释放，美味口感，轻轻放<br/>
					纵。
				</view>
		    </view>
			<view class="small-text">
				*参考GB28050-2011《食品安全国家标准 预包装食品营养<br/>
				标签通则》
			</view>
		</view>
	    <!-- 2图与字 -->	
		<view id="two" class="same">
			<image src="../../static/menu/sessionSelect/big2.jpg" mode=""></image>
		    <view class="one-text">
		    	<text class="title" style="margin-left: 250rpx;">轻盈夏日甜点</text>
		    	<view class="text-content">
		    		轻盈的夏日甜点来啦！<br/>
		    		第一层铺上清爽果肉，<br/>
		    		第二层采用了核桃植物酸奶混合着火龙果果<br/>
		    		肉，<br/>
		    		第三层混合奇亚籽等食材，<br/>
		    		多种水果清香混合着核桃植物酸奶的醇香，<br/>
		    		层次丰富，口感轻盈顺滑。
		    	</view>
		    </view>
		</view>
	    <!-- 3图与字 -->
	    <view id="two" class="same">
	    	<image src="../../static/menu/sessionSelect/big3.jpg" mode=""></image>
	        <view class="one-text">
	        	<text class="title" style="margin-left: 280rpx;">开启新一天</text>
	        	<view class="text-content">
	        		两款餐包全新上市，开启美好新一天！<br/>
	        		有料小软欧融合了经典欧包和日式软包的长<br/>
	        		处，<br/>
	        		散发自然麦香，柔软细腻，<br/>
	        		慢慢馅料更适合东方人的口味。<br/>
	        		云朵布里欧内含三种口味，入口柔软，齿颊留<br/>
	        		香。
	        	</view>
	        </view>
	    </view>
	    <!-- 4图与字 -->
	    <view id="two" class="same">
	    	<image src="../../static/menu/sessionSelect/big4.jpg" mode=""></image>
	        <view class="one-text">
	        	<text class="title" style="margin-left: 280rpx;">活力一夏</text>
	        	<view class="text-content">
	        		本季星巴克小熊队长在炎炎夏日，<br/>
	        		带领我们一起感受生活美好！<br/>
	        		随卡附赠1个运动小熊摆件(3款随机)并以当<br/>
	        		下<br/>
	        		热门的盲盒方式，在开盒瞬间增加神秘惊喜。<br/>
	        		小熊四肢可以扭动，坐着的造型还能放名片或<br/>
	        		卡片，<br/>
					可爱且实用，为夏日增加一抹"星"意。
	        	</view>
	        </view>
	    </view>
	    <!-- 5图与字 -->
	    <view id="two" class="same">
	    	<image src="../../static/menu/sessionSelect/big5.jpg" mode=""></image>
	        <view class="one-text">
	        	<text class="title" style="margin-left: 300rpx;">沁爽盛夏</text>
	        	<view class="text-content">
	        		这一季我们来到美丽广阔的非洲，<br/>
	        		开启这趟盛夏咖啡之旅。<br/>
	        		卢旺达咖啡的成功<br/>
	        		离不开当地妇女坚韧不拔的精神力量。<br/>
	        		几十年来，她们团结一新致力于咖啡事业之<br/>
	        		中，<br/>
	        		也带来了这款带有精致柑橘般风味，<br/>
	        		伴有柔和蜂蜜般甜感的<br/>
	        		星巴克®单一产地系列卢旺达咖啡豆。<br/>
	        		而来自东非大裂谷的星巴克®东非大裂谷综合咖<br/>
	        		啡豆<br/>
	        		它带有迷人黑胡椒般的香气，，<br/>
	        		淡淡的黑巧克力与柑橘般的甜蜜风味。
	        	</view>
	        </view>
	    </view>
	    <!-- 6图与字 -->
	    <view id="two" class="same">
	    	<image src="../../static/menu/sessionSelect/big6.jpg" mode=""></image>
	        <view class="one-text">
	        	<text class="title" style="margin-left: 150rpx;">夏日乐悠悠 臻选一杯好咖啡</text>
	        	<view class="text-content">
	        		 这个夏天我们为你臻选来自阳光地带的热情咖<br/>
	        		 啡豆<br/>
	        		 卢旺达阿巴坤达卡瓦咖啡豆，<br/>
	        		 具有柑橘般的酸甜风味，并伴有全麦饼干和牛<br/>
	        		 轧糖般的香醇<br/>
	        		 哥斯达黎加蜜处理咖啡豆，<br/>
	        		 拥有红苹果般的柔和香气，伴随着李子干和甘<br/>
					 蔗般的甜感<br/>
					 卢旺达穆洪多咖啡豆具有可可粉和红糖般的风<br/>
					 味，<br/>
					 伴有麦芽般的底韵，口感平衡。
	        	</view>
	        </view>
	    </view>
	    <!-- 所有新品 -->
		<view class="bottom-container">
			<!-- 文字 -->
			<view class="all">所有新品</view>
			<!-- 13个小块 -->
			<view class="small-block">
				<!-- 各个小块 -->
				<view class="every-list" v-for='(item,index) in everyList' :key='item.index'>
					<image :src="item.url" mode=""></image>
				    <view>{{item.text}}</view>
				</view>
			</view>
		</view>
	    <!-- 搜索菜单 -->
		<view class="search-menu">
			搜索菜单
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				everyList:[
					{
						url:'../../static/menu/sessionSelect/small1.jpg',
						text:'百香果桃桃茶云乌龙'
					},
					{
						url:'../../static/menu/sessionSelect/small2.jpg',
						text:'火龙果番石榴茶云乌龙'
					},
					{
						url:'../../static/menu/sessionSelect/small3.jpg',
						text:'玫香葡萄茶云乌龙'
					},
					{
						url:'../../static/menu/sessionSelect/small4.jpg',
						text:'果莓植物酸奶巴菲杯'
					},
					{
						url:'../../static/menu/sessionSelect/small5.jpg',
						text:'有料小软软'
					},
					{
						url:'../../static/menu/sessionSelect/small6.jpg',
						text:'云朵布里欧'
					},
					{
						url:'../../static/menu/sessionSelect/small7.jpg',
						text:'哥斯达黎加蜜处理咖啡'
					},
					{
						url:'../../static/menu/sessionSelect/small8.jpg',
						text:'卢旺达阿巴坤达卡瓦咖啡'
					},
					{
						url:'../../static/menu/sessionSelect/small9.jpg',
						text:'卢旺达穆洪多咖啡'
					},
					{
						url:'../../static/menu/sessionSelect/small10.jpg',
						text:'星巴克®单一产地系列卢旺达咖啡豆'
					},
					{
						url:'../../static/menu/sessionSelect/small11.jpg',
						text:'百香果桃桃茶云乌龙'
					},
					{
						url:'../../static/menu/sessionSelect/small12.jpg',
						text:'星巴克®东非大裂谷综合咖啡豆'
					},
					{
						url:'../../static/menu/sessionSelect/small13.jpg',
						text:'活力夏日会员星礼包'
					}
				]
			};
		}
	}
</script>

<style lang="scss">
     .container {
		 margin-bottom: 200rpx;
		 position: relative;
		 .top-menu {
			 height: 60rpx;
			 width: 90rpx;
			 font-size: 44rpx;
			 color: rgba(0,0,0,0.87);
			 font-weight: 900;
			 margin: 40rpx 0 40rpx 40rpx;
		 }
	     .selected-line {
			 font-size: 32rpx;
			 color: rgba(0,0,0,0.87);
			 display: flex;
			 margin-left: 40rpx;
			 view {
				 margin:0 50rpx 0 0;
			 }
		 }	 
	     .line {
			 margin-top: 25rpx;
			 width: 750rpx;
			 height: 2rpx;
			 background-color: #e8ebc8;
		 }
	     .same {
			 image {
				 width: 750rpx;
				 height: 750rpx;
				 margin-bottom: 60rpx;
			 }
		     .title {
				 width: 750rpx;
				 height: 56rpx;
				 font-size: 40rpx;
				 color: #000;
				 margin-left: 220rpx;
			 }
			 .text-content {
				 width: 750rpx;
				 height: 520rpx;
				 color: rgba(0,0,0,0.87);
				 font-size: 32rpx;
				 text-align: center;
				 line-height: 60rpx;
				 margin: 30rpx 0 0rpx 0;
			 }
		     .small-text {
				 color: rgba(0,0,0,0.87);
				 font-size: 24rpx;
				 height: 80rpx;
				 width: 648rpx;
				 text-align: center;
				 margin: -50rpx 0 80rpx 40rpx;
			  }
		 }
	     .bottom-container {
			 background-color: #f7f7f7;
			 .all {
				 width: 750rpx;
				 height: 56rpx;
				 font-size: 40rpx;
				 color: #000;
				 background-color: #f7f7f7;
				 padding-top: 90rpx;
				 margin-top: 200rpx;
				 text-align: center;
			 }
		     .small-block {
				 font-size: 32rpx;
				 display: flex;
				 flex-wrap: wrap;
				 margin-left: 20rpx;
				 .every-list {
					 width: 350rpx;
					 height: 460rpx;
					 margin-top: 50rpx;
					 image {
						 width: 300rpx;
						 height: 343.2rpx;
						 padding: 24rpx;
					 }
					 view {
						 width: 343.2rpx;
						 height: 51rpx;
						 color: rgba(0,0,0,0.87);
						 text-align: center;
					 }
				 }
			 }
		 }
	     .search-menu {
			 color: #fff;
			 background-color: #00a862;
			 width: 228rpx;
			 height: 104rpx;
			 border-radius: 48rpx;
			 text-align: center;
			 line-height: 104rpx;
			 font-size: 32rpx;
			 font-weight: 900;
			 position: fixed;
			 bottom: 120rpx;
			 right: 20rpx;
		}
	 }
</style>
