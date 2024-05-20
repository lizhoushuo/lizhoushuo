<template>
	<div>


				<!-- <img src="../assets/image/标题.png" alt="" style="width: 100%" /> -->
				<div class="place">
					<div class="places" @mouseover="over" @mouseleave="leave">
						<img v-show="flag == false" src="../assets/image/组 230@2x.png" alt="">
						<img v-show="flag == true" src="../assets/image/组 230@2x(1).png" alt="">
						<p>科研块地1</p>
						<p>[京都1号]</p>
					</div>
					<div class="places2" @mouseover="over2" @mouseleave="leave2">
						<img v-show="flag2 == false" src="../assets/image/组 230@2x.png" alt="">
						<img v-show="flag2 == true" src="../assets/image/组 230@2x(1).png" alt="">
						<p>科研块地2</p>
						<p>[京都2号]</p>
					</div>
					<div class="places3" @mouseover="over3" @mouseleave="leave3">
						<img v-show="flag3 == false" src="../assets/image/组 230@2x.png" alt="">
						<img v-show="flag3 == true" src="../assets/image/组 230@2x(1).png" alt="">
						<p>科研块地3</p>
						<p>[京都3号]</p>
					</div>
					<div class="places4" @mouseover="over4" @mouseleave="leave4">
						<img v-show="flag4 == false" src="../assets/image/组 230@2x.png" alt="">
						<img v-show="flag4 == true" src="../assets/image/组 230@2x(1).png" alt="">
						<p>科研块地4</p>
						<p>[京都4号]</p>
					</div>
				</div>
				<div class="box" v-show="status == true">
					<div class="top">
						<img src="../assets/image/容器 47@2x.png" alt="">
						<h4>科研块地1&ensp;[京都1号]</h4>
					</div>
					<div class="midlle">
						<img src="../assets/image/蒙版组 3@2x.png" alt="">
						<img src="../assets/image/蒙版组 6@2x.png" alt="">
					</div>
					<p>扫码查看视频过程</p>
				</div>
				<div class="box2" v-show="status2 == true">
					<div class="top">
						<img src="../assets/image/容器 47@2x.png" alt="">
						<h4>科研块地2&ensp;[京都2号]</h4>
					</div>
					<div class="midlle">
						<img src="../assets/image/蒙版组 3@2x.png" alt="">
						<img src="../assets/image/蒙版组 6@2x.png" alt="">
					</div>
					<p>扫码查看视频过程</p>
				</div>
				<div class="box3" v-show="status3 == true">
					<div class="top">
						<img src="../assets/image/容器 47@2x.png" alt="">
						<h4>科研块地3&ensp;[京都3号]</h4>
					</div>
					<div class="midlle">
						<img src="../assets/image/蒙版组 3@2x.png" alt="">
						<img src="../assets/image/蒙版组 6@2x.png" alt="">
					</div>
					<p>扫码查看视频过程</p>
				</div>
				<div class="box4" v-show="status4 == true">
					<div class="top">
						<img src="../assets/image/容器 47@2x.png" alt="">
						<h4>科研块地4&ensp;[京都4号]</h4>
					</div>
					<div class="midlle">
						<img src="../assets/image/蒙版组 3@2x.png" alt="">
						<img src="../assets/image/蒙版组 6@2x.png" alt="">
					</div>
					<p>扫码查看视频过程</p>
				</div>



	</div>
</template>

<script>
export default {
	name: '',
	components: {},
	data () {
		return {
			flag: false,
			flag2: false,
			flag3: false,
			flag4: false,
			status: false,
			status2: false,
			status3: false,
			status4: false,
		}
	},
	created () { },
	mounted () { },
	methods: {
		over () {
			this.flag = true
			this.status = true
		},
		leave () {
			this.flag = false
			this.status = false
		},
		over2 () {
			this.flag2 = true
			this.status2 = true
		},
		leave2 () {
			this.flag2 = false
			this.status2 = false
		},
		over3 () {
			this.flag3 = true
			this.status3 = true
		},
		leave3 () {
			this.flag3 = false
			this.status3 = false
		},
		over4 () {
			this.flag4 = true
			this.status4 = true
		},
		leave4 () {
			this.flag4 = false
			this.status4 = false
		},
	}
}
</script>
<style scoped lang='scss'>
.dv-border-box-6 {
	// background-image: url(../assets/image/bg\(1\).png);
	// background-size: 100% 100%;
	// background-repeat: no-repeat;
	// background-position: center;
	// height: 100%;
	// width: 100%;
	// background-color: #0d1d17;
	// border: 1px solid #ccc;
	// position: relative;

	.place {
		color: #fff;

		.places {
			position: absolute;
			top: 176px;
			left: 728px;

		}

		.places2 {
			position: absolute;
			top: 304px;
			left: 856px;
		}

		.places3 {
			position: absolute;
			top: 578px;
			left: 937px;
		}

		.places4 {
			position: absolute;
			top: 548px;
			left: 1096px;
		}
	}

	.box {
		width: 250px;
		background-color: rgb(0, 0, 0, 0.6);
		border-radius: 8px;
		color: #fff;
		position: absolute;
		top: 5px;
		left: 766px;
		border: 2px solid #205654;
    z-index: 10px;
		.top {
			padding: 10px;
			box-sizing: border-box;
			display: flex;
			align-items: center;
			border-bottom: 1px solid #42564b;

			img {
				margin-right: 10px;
			}
		}

		.midlle {
			display: flex;
			justify-content: space-between;
			align-items: center;
			padding: 10px 20px;
			box-sizing: border-box;
      background-color: rgba(0, 0, 0, .6);


			img {
				width: 98px;
				height: 98px;
			}
		}

		p {
			text-align: center;
			font-size: 14px;
			padding-bottom: 10px;
			box-sizing: border-box;
		}
	}
	.box2 {
		width: 250px;
		background-color: rgb(0, 0, 0, 0.6);
		border-radius: 8px;
		color: #fff;
		position: absolute;
		top: 90px;
		left: 895px;
		border: 2px solid #205654;

		.top {
			padding: 10px;
			box-sizing: border-box;
			display: flex;
			align-items: center;
			border-bottom: 1px solid #42564b;

			img {
				margin-right: 10px;
			}
		}

		.midlle {
			display: flex;
			justify-content: space-between;
			align-items: center;
			padding: 10px 20px;
			box-sizing: border-box;

			img {
				width: 98px;
				height: 98px;
			}
		}

		p {
			text-align: center;
			font-size: 14px;
			padding-bottom: 10px;
			box-sizing: border-box;
		}
	}
	.box3 {
		width: 250px;
		background-color: rgb(0, 0, 0, 0.6);
		border-radius: 8px;
		color: #fff;
		position: absolute;
		top: 370px;
		left: 975px;
		border: 2px solid #205654;

		.top {
			padding: 10px;
			box-sizing: border-box;
			display: flex;
			align-items: center;
			border-bottom: 1px solid #42564b;

			img {
				margin-right: 10px;
			}
		}

		.midlle {
			display: flex;
			justify-content: space-between;
			align-items: center;
			padding: 10px 20px;
			box-sizing: border-box;

			img {
				width: 98px;
				height: 98px;
			}
		}

		p {
			text-align: center;
			font-size: 14px;
			padding-bottom: 10px;
			box-sizing: border-box;
		}
	}
	.box4 {
		width: 250px;
		background-color: rgb(0, 0, 0, 0.6);
		border-radius: 8px;
		color: #fff;
		position: absolute;
		top: 340px;
		left: 1135px;
		border: 2px solid #205654;

		.top {
			padding: 10px;
			box-sizing: border-box;
			display: flex;
			align-items: center;
			border-bottom: 1px solid #42564b;

			img {
				margin-right: 10px;
			}
		}

		.midlle {
			display: flex;
			justify-content: space-between;
			align-items: center;
			padding: 10px 20px;
			box-sizing: border-box;

			img {
				width: 98px;
				height: 98px;
			}
		}

		p {
			text-align: center;
			font-size: 14px;
			padding-bottom: 10px;
			box-sizing: border-box;
		}
	}
}
</style>
