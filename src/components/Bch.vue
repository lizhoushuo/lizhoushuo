<template>
	<div class="bch">
		<div style="border-bottom: 2px solid #43544c;height: 50px;display: flex;align-items: center;">
			<img src="../assets/image/容器 47@2x.png" alt="" style="margin-left: 20px;">
			<p style="font-size: 20px;color: #a3b9af;font-weight: 800;margin-left: 10px;font-family: SimSun;">
				病虫害检测预警</p>
		</div>
		<div class="di">
			<img src="../assets/image/图层 2@2x.png" alt="">
			<p class="xian"></p>
			<p class="zi">专审建议:西香国文计土播通店旧布韩路频建安讹播黄国国，光线完足的坡。主球主2沙圆内。你冠士场性溶正学，全所注。这日克水，仅持主球想开但不配水。</p>
		</div>
	</div>
</template>

<script>
export default {
	name: '',
	components: {},
	data () {
		return {
		}
	},
	created () { },
	mounted () { },
	methods: {}
}
</script>
<style scoped lang='scss'>
.bch {
	width: 460px;
	height: 240px;
	border: 2px solid #43544c;
	position: fixed;
	bottom: 40px;
	right: 50px;
	border-radius: 10px;
	background-color: rgb(0, 0, 0, 0.5);

	.top {
		color: #fff;
		display: flex;
		align-items: center;
		padding: 20px;
		box-sizing: border-box;
		border-bottom: 3px solid #43544c;

		p {
			font-size: 20px;
			color: rgb(163, 185, 175);
			font-weight: 800;
			margin-left: 10px;
			font-family: SimSun;
		}
	}

	.di{
		display: flex;
		align-items: center;
		padding: 20px;
		box-sizing: border-box;
		.xian{
			width: 2px;
			height: 120px;
			background-color: #5f5f5f;
			margin: 0 10px;
		}
		.zi{
			color: #fff;
		}
	}
}
</style>
