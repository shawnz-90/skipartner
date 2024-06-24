<template>
	<view>
		<image :src="picurl" mode=""></image>
		<input type="text" />
	</view>
	<view class="box" :class="{active:isActive}">
		v-bind instra
	</view>
<!-- 	<view class="box" :class="isActive ? 'active':''">
		v-bind instra
	</view> -->
	<view class="box" :style="{width: '300px',height: 260+'px',fontSize:size+'px'}">
			v-bind instra
	</view>
	
	
	
</template>

<script setup>

import {ref} from "vue";
const picurl= ref("../../static/2.png");
const arrs= ref(["../../static/1.png","../../static/2.png","../../static/5.png"]);
const isActive = ref(false);
const size = ref(30);


// setInterval(()=>{
	
// 	size.value = size.value+1;
// },1000)



</script>

<style lang="scss">

.box{
	width: 200px;
	height: 200px;
	background: red;
	font-size: 20px;
}
.active{
	background: green;
	color:#fff
	
}
</style>
