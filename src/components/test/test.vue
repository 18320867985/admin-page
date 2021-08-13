<template>
	<div class="pp">{{test}}
	<hr>
	<input type="text" name="" id="" value="" v-model="test" />
	</div>
</template>

<script>
	export default{
		data(){
			return {
				test:"vue-dev hqs 6688"
			}
		}
	}
</script>

<style scoped="">
	.pp{
		font-size: 30px;
		color:red;
	}
</style>
