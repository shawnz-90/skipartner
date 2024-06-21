<template>
{{num1}}
</template>

<script setup>
import {ref} from "vue";
let num2 = ref(10);


let num1 = 6;
console.log(num1)
console.log(num2)
/* setInterval(()=>{
	num1++;
	console.log(num1)
},1000)
 */
</script>

<style>

</style>
