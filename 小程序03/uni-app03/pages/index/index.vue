<template>
	<view>
		<text class="home-title">文本</text>

		<view class="home-title">
			<text user-select="true">文字可以选中</text>
		</view>
		<view class="home-title">
			<text selectable="true">文字可以选中</text>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: ''
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin-top: 200rpx;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 50rpx;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
	.home-title {
		padding: 10px;
		font-size: 16px;
		
	}
</style>
