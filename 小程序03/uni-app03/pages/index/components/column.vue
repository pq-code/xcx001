<template>
	<!-- <view class="column-container" v-for="item of datas">
		<view>
			<Card :data="item"/>
			<Card :data="item"/>
		</view>
	</view> -->
	<view class="column-container" v-for="item of datas">
		<Card/>
		<Card/>
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
		/* background-color: #d8dbe6; */
	}
</style>
