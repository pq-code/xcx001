<template>
	<view class="topNavigation-container">
		<view class="navbar"> 
			推荐
		</view>
	</view>
	<view class="bottom-container">
		<view>
			正品保障
		</view>
		<view>
			逐件查验
		</view>
		<view>
			多重鉴别
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: ['推荐','鞋类','潮服','手表','箱包','配饰','数码','美妆','潮服','运动','女装','出行'],
			}
		},
	}
</script>

<style scoped>
	.topNavigation-container {
		width: 100%;
		height: 80rpx;
		background-color: #eef4f9;
	}
	.navbar {
		width: 100%;
		height: 70rpx;
		background-color: #babebe;
		align-items: center;
	}
	.bottom-container {
		display: flex;
		font-size: 26rpx;
	}
</style>
