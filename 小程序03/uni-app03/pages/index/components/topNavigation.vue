<template>
	<view class="status_bar">
		<Search/>
		<view class="navbar">
			推荐 鞋类 潮服 手表 箱包 配饰 数码
		</view>
	</view>
</template>

<script>
	import Search from './search.vue';
	export default {
		components:{
			Search,
		},
		data() {
			return {
				title: ['推荐','鞋类','潮服','手表','箱包','配饰','数码','美妆','潮服','运动','女装','出行'],
			}
		},
	}
</script>

<style scoped>
	.status_bar {
	       height: var(--status-bar-height);
	       width: 100%;
	   }
	.navbar {
		width: 100%;
		height: 70rpx;
		font-size: 36rpx;
		background-color: #faffff;
		align-items: center;
		padding-left:20rpx;
	}

</style>
