<template>
	<view class="content">
		<view>
			<image src="../../static/clam.gif" mode="aspectFill"/>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: '这是我的第一个小程序'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.status_bar {
		height: 60px;
		width: 100%;
	}

	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
</style>