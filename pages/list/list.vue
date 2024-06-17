<template>
	<view>
		<view class="box"></view>
		<view class="block"></view>
		<icon type="success" size="26" />
		<view>123</view>
		<view>111</view>
		<text>1</text>
		<text space="emsp">2</text>
		<scroll-view scroll-x scroll-y class="scroll">
			<view class="group">
				<view class="item">
					11
				</view>
				<view class="item">
					11
				</view>
				<view class="item">
					11
				</view>
				<view class="item">
					11
				</view>
				<view class="item">
					11
				</view>
			</view>
		</scroll-view>
	</view>
</template>

<script>
	export default {
		data() {
			return {}
		},
		methods: {

		}
	}
</script>

<style lang="scss">
	.box {
		width: 200px;
		height: 200px;
		background: black;
	}

	.block {
		width: 750rpx;
		height: 200rpx;
		background: pink;
	}

	.scroll {
		border: 1px solid red;
		box-sizing: border-box;
		height: 110rpx;
		.group{
			white-space: nowrap;
			.item{
				width: 220rpx;
				height: 220rpx;
				background: blue;
				display: inline-block;
				margin-right: 12rpx;
			}
		}
	}
</style>