<template>
	<view>
		<view class="header">
			<view class="header-left" @click="gotoleft">
				<image src="../../static/left.png" mode=""></image>
			</view>
			<view class="header-content">
				账户设置
			</view>
			<view class="header-right">
				<!-- <image src="../../static/sousuo.png" mode=""></image> -->
			</view>
		</view>

		<view class="body-content">
			<view class="list-box">
				<ul>
					<li>
						<span class="list-item-title">碧波号</span>
						<span class="list-item-content">Bbobi8888888</span>
					</li>
					<li>
						<span class="list-item-title">手机号</span>
						<span class="list-item-content">18888888888</span>
					</li>
					<li>
						<span class="list-item-title">登录邮箱</span>
						<span class="list-item-content">Bbobi888@163.com</span>
					</li>
				</ul>
			</view>

			<view class="list-box height-margin">
				<ul>
					<li>
						<span class="list-item-title">修改密码</span>
						<image src="../../static/right_01.png"></image>
					</li>
					<!-- <li>
						<span class="list-item-title">碧波世界安全中心</span>
						<image src="../../static/right_01.png"></image>
					</li> -->
				</ul>
			</view>
		</view>

	</view>
</template>

<script>
	export default {
		data() {
			return {}
		},
		onLoad() {

		},
		methods: {
			gotoleft: function () {
				uni.navigateBack({
					delta: 1
				})
			},
		}

	}
</script>

<style>
	.header {
		height: 0.88rem;
		width: 100%;
		display: flex;
		background: #fff;
		align-items: center;
		box-shadow: 0px 2px 4px 0px rgba(238, 238, 238, 0.5);
	}


	.header-left,.header-right {
		min-width: 1rem;
		display: flex;
		align-items: center;
		justify-content: center;
	}

	.header-left image {
		width: 0.4rem;
		height: 0.4rem;
	}

	.header-content {
		flex: 1;
		overflow: hidden;
		display: flex;
		justify-content: center;
		font-size: 0.36rem;
	}

	.body-content {
		text-align: center;
	}

	.list-box {
		margin: 0.2rem;
		padding: 0 0.4rem;
		background: #fff;
		border-radius: 0.1rem;
		padding-bottom: 0.2rem;
	}

	.height-margin {
		margin-top: 0.4rem;
	}

	.list-box li {
		padding-top: 0.2rem;
		border-bottom: 1px solid #eee;
		height: 1rem;
		line-height: 1rem;
		font-size: 0.32rem;
		display: flex;
		justify-content: space-between;
	}
	
	
	.list-item-title {
		font-family: PingFangSC-Medium;
		font-size: 24px;
		font-weight: normal;
		font-stretch: normal;
		letter-spacing: 0px;
		color: #606060;
	}

	.list-item-content {
		color: #b6b6b6;
	}

	.list-box li image {
		width: 0.2rem;
		height: 0.2rem;
		margin-top: 0.5rem;
	}
</style>
