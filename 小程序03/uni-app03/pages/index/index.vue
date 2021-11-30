<template>	
	<view class="container">
		<view class="top">
			<Search/>
			<TopNavigation/>
		</view>
		
		<view class="content">
			<Column/>
		</view>
		
	</view>
	
</template>

<script>
	// 
	import Search from './components/search.vue';
	import TopNavigation from './components/topNavigation.vue';
	import Column from './components/column.vue';
	
	export default {
		components:{
			Search,
			TopNavigation,
			Column,
		},
		data() {
			return {
				title: '',
				searchItem:'',
			}
		},
		onLoad() {

		},
		onReachBottom() {
			console.log('页面触底了');
		},
		methods: {
			search(){
				console.log('1', this.searchItem);
			}
		}
	}
</script>

<style scoped>
	.container {
		background-color: #e5ebf0;
		width: 100%;
		height: 100%;
	}
	.top {
		width: 100%;
		height: 260rpx;
		background-color: #FFFFFF;
		/* border-bottom:1px solid #000 ; */
	}.content {
		width: 100%;
		height: 100%;
		margin-top: 20rpx;
		background-color: #eef3f3;
	}
</style>
