<template>	
	<view class="container">
		<view class="top">
			<TopNavigation/>
		</view>
		
		<view class="content">
			<Title/>
			<Column/>
		</view>
		
	</view>
	
</template>

<script>
	// 
	import Search from './components/search.vue';
	import TopNavigation from './components/topNavigation.vue';
	import Column from './components/column.vue';
	import Title from './components/title.vue';
	export default {
		components:{
			Search,
			TopNavigation,
			Column,
			Title,
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
		height: 180rpx;
		background-color: #FFFFFF;
		/* border-bottom:1px solid #000 ; */
	}.content {
		width: 100%;
		height: 100%;
		background-color: #F1F1F1;
	}
</style>
