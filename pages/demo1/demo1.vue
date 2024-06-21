<template>
	<view>
		<swiper indicator-dots="true" autoplay="true" interval="3000" duration="1000" circular
		vertical
		>
			<swiper-item>
				<view class="swiper-item"><image src="../../static/1.png" mode="aspectFill"></image></view>
			</swiper-item>
			<swiper-item>
				<view class="swiper-item"><image src="../../static/2.png" mode="aspectFill"></image></view>
			</swiper-item>
			<swiper-item>
				<view class="swiper-item"><image src="../../static/5.png" mode="aspectFill"></image></view>
			</swiper-item>
			<swiper-item>
				<view class="swiper-item"><image src="../../static/6.png" mode="aspectFill"></image></view>
			</swiper-item>
		</swiper>
	</view>
	<view>
		<image src="../../static/logo.png" mode="" class="pic1"></image>
		<image src="../../static/1.png" mode="aspectFit" class="pic2"></image>
		<image src="../../static/5.png" mode="widthFix" class="pic3"></image>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			
		}
	}
</script>

<style lang="scss">
swiper{
	width: 100vw;
	height: 200px;
	border: 1px solid red;
	swiper-item{
		width: 100%;
		height: 100%;
		background: pink;
		image{
			width: 100%;
			
			
		}
	}

	
	
}
.pic1{
	width: 150px;
	height: 150px;
	
}
.pic2{
	width: 200px;
	height: 200px;
}
.pic3{
	widows: 300px;
}
</style>
