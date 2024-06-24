<template>

{{obj.name}}
</template>

<script setup>
import {ref} from "vue";
let num2 = ref(10);
let test=ref("shawn")
let obj = ref({name:"shun",age:18})
obj.value.name="who"
// console.log(num2.value)
// setInterval(()=>{
// 	num2.value++;
// 	console.log(num2.value)
// },1000)

</script>

<style>

</style>
