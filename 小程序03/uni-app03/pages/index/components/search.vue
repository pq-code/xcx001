<template>
	<view class="search-view">
		<input type="text" value="" placeholder="搜索单品" class="search-input" disabled />
		<view class="search-image-view">
			<image mode="widthFix" class="search-image" src="../../../static/coen/iconfangp.png"></image>
		</view>
	</view>
</template>

<script>
</script>

<style scoped>
	.search-view {
		height: 100rpx;
		width: 100%;
		display: flex;
		align-items: center;
	}
	.search-input {
		width: 68%;
		height: 66rpx;
		margin: 10rpx 0 10rpx 40rpx; 
		padding: 0 20rpx 0 70rpx;
		background-color: #f2f9fe;
		border-radius: 4rpx;
	}
	.search-image-view {
		width: 64rpx;
		height: 64rpx;
		margin: 10rpx 25rpx 10rpx 25rpx;
	}
	.search-image {
		width: 100%;
		height: 1000%;
	}
</style>
