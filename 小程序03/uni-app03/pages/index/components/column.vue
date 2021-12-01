<template>
	<view class="column-container">
		<view class="column-card" v-for="item of datas">
			<Card/>
		</view>
	</view>
</template>

<script>
	import Card from './card.vue';
	
	export default {
		components:{
			Card,
		},
		data() {
			return {
				datas: [
					{
						title: '阿迪王',
						price: '¥300',
						briefIntroduction: '黑心棉花',
					},
					{
						title: '奶克',
						price: '¥200',
						briefIntroduction: '黑心棉花',
					},
					{
						title: '李拧',
						price: '¥200',
						briefIntroduction: '双十一12折',
						
					},
					{
						title: '按塔',
						price: '¥200',
						briefIntroduction: '双十一12折',
					},
					{
						title: '按塔',
						price: '¥200',
						briefIntroduction: '双十一12折',
					},
					{
						title: '按塔',
						price: '¥200',
						briefIntroduction: '双十一12折',
					}
				]
			}
		}
	}
</script>
	
<style scoped>
	.column-container {
		width: 100%;
		height: 100%;
		display: flex;
		margin: 2% 2% 2% 0;
		flex-wrap: wrap; /* 换行 */
		/* background-color: #d8dbe6; */
		/* padding: 4rpx 4rpx 4rpx 0; */
	}
	.column-card {
		width: 50%;
		height: 50%;
		/* padding: 4rpx 4rpx 4rpx 0; */
		/* margin: 4rpx 4rpx 4rpx 0; */
	}
</style>
