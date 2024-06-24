<template>
	<view class="box" @click="onClick" :style="{background:color}">
		{{num}}
	</view>
	<switch checked="true" @change="OnChange" />
	<button type="primary" :loading="isLoading">bbc</button>
</template>

<script setup>

import {ref} from "vue";
const num = ref(1)
const color = ref("#fc359a");
const isLoading = ref(true)
	
function onClick(){
	color.value="#"+String(Math.random()).substring(3,9)
	num.value = String(Math.random()).substring(3,9)
};

function OnChange(e){
	isLoading.value=e.detail.value
}
</script>

<style>
.box{
	width: 200px;
	height: 200px;
	background: red;
}      
</style>
