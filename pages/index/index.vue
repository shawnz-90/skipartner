
<template>
	<view class="">
		<navigator url="/pages/demo1/demo1" open-type="reLaunch">go to demo1</navigator>
		<navigator url="/pages/demo2/demo2">go to demo2</navigator>
	</view>
	<view class="box" hover-class="boxHover">
	<view class="inner" hover-class="innerHover">inner</view>
	</view>
	<scroll-view scroll-x="true" class="scrollView">
		<view class="box">sub element</view>
		<view class="box">sub element</view>
		<view class="box">sub element</view>
	
	
	</scroll-view>
</template>

<script setup>

</script>


<style lang="scss">
.scrollView{
	width: 80%;
	height: 220px;
	border: 1px solid red;
	white-space: nowrap;
	.box{
		width: 100px;
		height: 100px;
		background: green;
		display: inline-block;
		margin: 5px;
	}
}

</style>
