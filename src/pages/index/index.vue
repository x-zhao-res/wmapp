<template>
	<view class="body">
		<view class="card">
			<view class="left">
			   <view class="font-use">希图斯</view>
			   <view class="icon"></view>
			</view>
			<view class="line"></view>
			<view class="right">
				<view class="font-day">白天</view>
				<view class="time">{{min}} 分 {{sec}} 秒</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello111',
				min:3,
				sec:15
			}
		},
		onLoad() {

		},
		methods:{

		}
	}
</script>

<style>
	.line{
		width: 4rpx;
		height: 240rpx;
		background-color: 	#778899;
	}
	.icon{
		width: 150rpx;
		height: 150rpx; 
		margin-top: 20rpx ;
		box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.5);
		border-radius: 30rpx;
	}
	.body{
		width: 750rpx;
		height: 100vh;
		display: flex;
		justify-content: center;
		position: relative;
	}
	.card{
		margin-top: 20rpx;
		width: 730rpx;
		height: 330rpx;
		display: flex;
		justify-content: space-between;
		align-items: center;
		box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.5);
        border-radius: 30px;
	}
	.left{
		width: 370rpx;
		height: 320rpx;
	   
	    display: flex;
	    justify-content: center; 
	  flex-wrap: wrap;
	}
	.right{
		width: 370rpx;
		height: 320rpx;
		display: flex;
		justify-content: center;
		flex-wrap: wrap;
	}
	.font-use{
		margin-top: 30rpx;
		text-align: center;
		 font-size: 60rpx;
        font-family: PingFangSC-Regular, PingFang SC;
		width:370rpx;
		height:80rpx;
		
		
	}
	.font-day{
		width: 300rpx;
		height: 60rpx;
		
		  font-family: PingFangSC-Regular, PingFang SC;
		   font-size: 60rpx;
		   text-align: center;
		   margin-top: 50rpx;
	}
	.time{
		width: 300rpx;
		height: 60rpx;
		text-align: center;
		
		margin-top: 10rpx;
		font-size: 50rpx;
	}
</style>
