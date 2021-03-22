<template>

	<view class="container">

		<view class="header">
			<button class="Settingbutton">1</button>
			<input class="input" focus placeholder="请输入搜索内容" />
			<button class="DownLoadbutton">1</button>
		</view>

		<view class="topmenulist">
			<se-button>1</se-button>
			<se-button>1</se-button>





		</view>


		<view class="content">

			<view class="leftcotent"></view>
			<view class="rightcotent"></view>

		</view>



	</view>

</template>

<script>
	export default {
		data() {
			return {
				href: 'https://uniapp.dcloud.io/component/README?id=uniui'
			}
		},
		methods: {

		}
	}
</script>

<style>
	.header {
		display: flex;
		text-align: center;
		font-family: uniicons;
		font-size: 24px;
		font-weight: normal;
		font-style: normal;
		width: 100%;
		padding: 0.5rem;
		height: 2rem;
		line-height: 2rem;
		color: #00ff00;
		background-color: #DCDFE6;
	}
	.Settingbutton {
		position: absolute;
		width: 1rem;
		height: 1rem;
		line-height: 1rem;
		text-align: center;
	}

	.DownLoadbutton {
		position: absolute;
		width: 1rem;
		height: 1rem;
		right: 0.5rem;
		line-height: 1rem;
		text-align: center;
	}

	.input {
		position: absolute;
		left: 5%;
		width: 90%;
		height: 1rem;
		line-height: 1rem;
		background-image: url(../../static/api.png);
		background-color: #2C405A;
	}

	.container {
		width: 100%;
		height:calc(100vh);;
		background-color: #797972;
	}

	.topmenulist {
		display: flex;
		text-align: center;
		position: relative;
		top: 1rem;
		height: 2rem;
		width: 100%;
		background-color: #007AFF;
	}

	.content {
		display: flex;
		margin-top: 2rem;
		width: 100%;
		height: 40rem;
		background-color: #aaaa7f;


	}
	.leftcotent {
		width: 20%;
		margin-right: 2%;
		height: 40rem;
		background-color: #AAAA7F;

	}

	.rightcotent {
		width: 78%;
		//
		height: 40rem;
		background-color: #51513c;
	}
</style>
