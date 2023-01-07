<template>
	<view id="box">
		<h2>果咩捏~欧尼酱!😅😅</h2>
		<div id="box01"></div>
		<div id="box02"></div>
		<icon type="success" size="26"/><br>
		<icon type="waiting" size="26"/><br>
		<icon type="warn" size="26"/><br>
		<text user-select selectable>唱</text>
		<text user-select selectable>rap</text>
		<text user-select selectable>rap</text>
		
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			};
		}
	}
</script>

<style lang="scss">
	#box{
		text-align: center;
	}
	#box01{
		width: 200px;
		height: 200px;
		background-color: aqua;
	}
	#box02{
		width: 200rpx;
		height: 200rpx;
		background-color: blue;
	}
</style>
