<template>
	<view>
		<view class="header">
			<view class="headerfix">
						<view class="search-color">
							<view class="search-left" @click="goback">
								<image src="../../static/sys.png" class="search-img"></image>
							</view>
							<view class="search-center">
								<view class="search">
									我的资产
								</view>
							</view>
							<view class="search-right">
								<image src="../../static/sousuo.png" class="search-img"></image>
							</view>
						</view>
						<view class="persion">
							<view class="persion-coin">6587457.514</view>
							<view class="persion-coin">CNY</view>
			
							<view class="persion-manage">
								<view class="persion-manage-sub" @click="gotoduihuan">
									<image src="../../static/jiaoyi_3.png" class="persion-manage-img"></image>
									<view class="text">兑换记录</view>
								</view>
								<view class="persion-manage-sub" @click="gotochongbi">
									<image src="../../static/chongbi.png" class="persion-manage-img"></image>
									<view class="text">充币记录</view>
								</view>
								<view class="persion-manage-sub" @click="gototibi()">
									<image src="../../static/tibijilu.png" class="persion-manage-img"></image>
									<view class="text">提币记录</view>
								</view>
							</view>
			
						</view>
					</view>
					
		</view>
		<scroll-view>
		<view class="renwu">
			<view class="renwu-title">
				<i class="renwu-i"></i>
				赚取碧波币
			</view>
			<view class="renwu-content">

				<view class="renwu-item mgr" @click="gotorenwuzhengbi">
					<image class="renwu_image" src="../../static/renwu.png"></image>
					<p>做任务挣币</p>
				</view>

				<view class="renwu-item mgl" @click="gotorenwuzhengbi_2">
					<image class="renwu_image2" src="../../static/renwu_2.png"></image>
					<p>玩游戏赚币</p>
				</view>
			</view>
		</view>
		<view>
			<view class="list" @click="gotoDetail">
				<view class="list-sub">
					<image src="../../static/bb.png" class="list-left"></image>
					<view class="list-center">
						<view class="list-title">bbb</view>
						<view class="list-des">(bibobi)</view>
					</view>
					<image src="../../static/right.png" class="list-right"></image>
				</view>
			</view>
			<view class="list">
				<view class="list-sub">
					<image src="../../static/bb.png" class="list-left"></image>
					<view class="list-center">
						<view class="list-title">bbb</view>
						<view class="list-des">(bibobi)</view>
					</view>
					<image src="../../static/right.png" class="list-right"></image>
				</view>
			</view>

			<view class="list">
				<view class="list-sub">
					<image src="../../static/bb.png" class="list-left"></image>
					<view class="list-center">
						<view class="list-title">bbb</view>
						<view class="list-des">(bibobi)</view>
					</view>
					<image src="../../static/right.png" class="list-right"></image>
				</view>
			</view>


			<view class="list">
				<view class="list-sub">
					<image src="../../static/bb.png" class="list-left"></image>
					<view class="list-center">
						<view class="list-title">bbb</view>
						<view class="list-des">(bibobi)</view>
					</view>
					<image src="../../static/right.png" class="list-right"></image>
				</view>
			</view>
			<view class="list">
				<view class="list-sub">
					<image src="../../static/bb.png" class="list-left"></image>
					<view class="list-center">
						<view class="list-title">bbb</view>
						<view class="list-des">(bibobi)</view>
					</view>
					<image src="../../static/right.png" class="list-right"></image>
				</view>
			</view>
			<view class="list">
				<view class="list-sub">
					<image src="../../static/bb.png" class="list-left"></image>
					<view class="list-center">
						<view class="list-title">bbb</view>
						<view class="list-des">(bibobi)</view>
					</view>
					<image src="../../static/right.png" class="list-right"></image>
				</view>
			</view>

			<view class="list">
				<view class="list-sub">
					<image src="../../static/bb.png" class="list-left"></image>
					<view class="list-center">
						<view class="list-title">bbb</view>
						<view class="list-des">(bibobi)</view>
					</view>
					<image src="../../static/right.png" class="list-right"></image>
				</view>
			</view>

			<view class="list">
				<view class="list-sub">
					<image src="../../static/bb.png" class="list-left"></image>
					<view class="list-center">
						<view class="list-title">bbb</view>
						<view class="list-des">(bibobi)</view>
					</view>
					<image src="../../static/right.png" class="list-right"></image>
				</view>
			</view>


			<view class="list">
				<view class="list-sub">
					<image src="../../static/bb.png" class="list-left"></image>
					<view class="list-center">
						<view class="list-title">bbb</view>
						<view class="list-des">(bibobi)</view>
					</view>
					<image src="../../static/right.png" class="list-right"></image>
				</view>
			</view>

			<view class="list">
				<view class="list-sub">
					<image src="../../static/bb.png" class="list-left"></image>
					<view class="list-center">
						<view class="list-title">bbb</view>
						<view class="list-des">(bibobi)</view>
					</view>
					<image src="../../static/right.png" class="list-right"></image>
				</view>
			</view>

			<view class="list">
				<view class="list-sub">
					<image src="../../static/bb.png" class="list-left"></image>
					<view class="list-center">
						<view class="list-title">bbb</view>
						<view class="list-des">(bibobi)</view>
					</view>
					<image src="../../static/right.png" class="list-right"></image>
				</view>
			</view>

			<view class="list">
				<view class="list-sub">
					<image src="../../static/bb.png" class="list-left"></image>
					<view class="list-center">
						<view class="list-title">bbb</view>
						<view class="list-des">(bibobi)</view>
					</view>
					<image src="../../static/right.png" class="list-right"></image>
				</view>
			</view>
			<view class="list">
				<view class="list-sub">
					<image src="../../static/bb.png" class="list-left"></image>
					<view class="list-center">
						<view class="list-title">bbb</view>
						<view class="list-des">(bibobi)</view>
					</view>
					<image src="../../static/right.png" class="list-right"></image>
				</view>
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
		onLoad() {

		},
		methods: {
			gototibi: function () {
				uni.navigateTo({
					url: "newtibijilu"
				})
			},
			gotoduihuan: function () {
				uni.navigateTo({
					url: "duihuanjilu"
				})
			},
			gotochongbi: function () {
				uni.navigateTo({
					url: "newchongbijilu"
				})
			},
			gotorenwuzhengbi() {
				uni.navigateTo({
					url: "renwuzhengbi"
				})
			},
			gotorenwuzhengbi_2() {
				uni.navigateTo({
					url: "renwuzhengbi_2"
				})
			},
			gotoDetail() {
				uni.navigateTo({
					url: "wealthDetail"
				})
			},
		}
	}
</script>

<style>
	page {
		background: #FFFFFF;
	}
	.header{
		height: 440px;
		width: 100%;
	}
	.headerfix {
		position: fixed;
		top: 0;
		left: 0;
		right: 0;
		z-index: 1;
	}

	.search-color {
		width: 100%;
		display: flex;
		overflow-x: hidden;
		flex-direction: row;
		background: #8cafea;
		height: 70px;
		padding-top: 40px;
	}

	.search-img {
		width: 40px;
		height: 40px;
		padding: 15px 30px;
	}

	.search-left {
		width: 100px;
		height: 100px;
	}


	.search {
		width: 530px;
		height: 40px;
		margin: 15px 10px;
		text-align: center;
		line-height: 40px;
		color: #FFFFFF;
	}

	.search-right {
		width: 100px;
		height: 100px;
	}

	.persion,
	.persion-coin,
	.persion-manage,
	.list,
	.wealth-bottom {
		width: 100%;
	}

	.persion {
		height: 370px;
		display: flex;
		flex-direction: column;
		background: #8cafea;
		/* background: #FFFFFF; */
	}

	.persion-coin {
		height: 100px;
		text-align: center;
		display: block;
		line-height: 100px;
		color: #FFFFFF;
	}

	.persion-manage {
		display: flex;
		flex-direction: row;
		height: 172px;
		background-color: #FFFFFF;
	}

	.persion-manage-sub {
		width: 33.33%;
		font-size: 25px;
		display: flex;
		align-items: center;
		justify-content: center;
		flex-direction: column;
		color: #FFFFFF;
		margin: 28px 0;
	}

	.persion-manage-img {
		width: 60px;
		height: 60px;
		margin-left: 20px;
	}

	.text {
		color: #8cafea;
		font-size: 28px;
		height: 50px;
		line-height: 50px;
		margin-top: 10px;
		margin-left: 20px;
	}

	.renwu {
		
		min-height: 320px;
		width: 100%;
		background: #f7f7f7;
		display: flex;
		flex-direction: column;
		padding-top: 40px;
		box-sizing: border-box;
		overflow: hidden;
	}

	.renwu-title {
		display: flex;
		height: 44px;
		width: 100%;
		margin-top: 40px;
		font-size: 32px;
		display: flex;
		align-items: center;
	}

	.renwu-i {
		display: block;
		width: 12px;
		height: 36px;
		margin: 0 20px;
		background-color: #8cafea;
	}

	.renwu-content {
		height: 220px;
		width: 100%;
		padding: 5% 0 0 5%;
		box-sizing: border-box;
		display: flex;
	}
	.renwu-item {
		width: 50%;
		height: 140px;
		display: flex;
		align-items: center;
		justify-content: center;
		flex-direction: column;
		background-color: #8cafea;
		border-radius: 16px;
		font-size: 28px;
		color: #ffffff;
		margin: 0 5% 5% 0;
	}

	.renwu_image {
		width: 50px;
		height: 60px;
	}

	.renwu_image2 {
		width: 60px;
		height: 60px;

	}

/* 	.mgr {
		margin-right: 5%;
	}

	.mgl {
		margin-left: 5%;
	} */


	.list {
		border-bottom: 2px solid #f2f2f2;
		height: 145px;
	}

	.list-sub {
		width: 700px;
		display: flex;
		flex-direction: row;
		margin: 0px 25px;
	}

	.list-left {
		width: 62px;
		height: 62px;
		margin-top: 40px;
	}

	.list-center {
		flex: 1;
		margin-left: 35px;
		margin-top: 35px;
	}

	.list-right {
		width: 30px;
		height: 30px;
		margin-top: 58px;
	}

	.list-title,
	.list-des {
		height: 30px;
		line-height: 30px;
		color: #6a6a6a;
	}

	.list-title {
		font-weight: bold;
	}

	.list-des {
		margin-top: 10px;
	}
</style>
