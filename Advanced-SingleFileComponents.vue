<template>
	<p>{{greeting}} world!</p>
</template>
<script>
	module.exports = {
		data(){
			return{
				greeting:'Hello',
			}
		}
	}
</script>
<style scoped>
	p{
		font-size:20px;
		text-align: center;
	}
</style>