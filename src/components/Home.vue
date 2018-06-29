<template>
	<div class="wrap">
		home页{{msg}}
	</div>
</template>

<script>
export default {
	name:'home',
	data(){
		return{
			msg:'hello'
		}
	}
}
</script>

<style>
.wrap{
	color: red;
}
</style>