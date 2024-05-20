<template>
	<div
		style="width: 460px;height: 250px;border-radius: 10px;border: 3px solid #43544c;background-color: rgba(0, 0, 0, .5);position: fixed;bottom: 40px;left: 525px;">
		<div style="border-bottom: 2px solid #43544c;height: 50px;display: flex;align-items: center;">
			<img src="../assets/image/容器 47@2x.png" alt="" style="margin-left: 20px;">
			<p style="font-size: 20px;color: #a3b9af;font-weight: 800;margin-left: 10px;font-family: SimSun;">
				土壤肥力分析</p>
		</div>

		<div
			style="height: 200px;height: 100%;display: flex;align-items: center;justify-content: space-between;position: relative;">
			<dv-active-ring-chart :config="config"
				style="width:300px;height:300px;position: absolute;top: -50px;left: 75px;" />
			<div>
				<p style="font-size: 14px;color: #e072e5;margin-top: 15px;margin-left: 20px;">有机物1 <span>12%</span></p>
				<p style="font-size: 14px;color: #dd965d;margin-top: 15px;margin-left: 20px">有机物2 <span>25%</span></p>
				<p style="font-size: 14px;color: #71e9de;margin-top: 15px;margin-left: 20px;margin-bottom: 80px;">有机物3 <span>13%</span></p>
			</div>
			<div>
				<p style="font-size: 14px;color: #d7d588;margin-top: 15px;margin-right: 20px;">有机物4 <span>25%</span></p>
				<p style="font-size: 14px;color: #5f96cc;margin-top: 15px;margin-right: 20px;">有机物5 <span>13%</span></p>
				<p style="font-size: 14px;color: #69d4b3;margin-top: 15px;margin-right: 20px;margin-bottom: 80px;">有机物6 <span>12%</span></p>
			</div>
		</div>

	</div>
</template>
<script>


export default {
	data () {
		return {
			config: {
				data: [
					{ name: "有机物1", value: 14 },
					{ name: "有机物2", value: 25 },
					{ name: "有机物3", value: 11 },
					{ name: "有机物4", value: 25 },
					{ name: "有机物5", value: 13 },
					{ name: "有机物6", value: 12 }
				],
				color: ["#e072e5", "#dd965d", "#71e9de", "#d7d588", "#5f96cc", "#69d4b3"],
				lineWidth: 8,
				digitalFlopStyle: {
					fontSize: 20,
					fill: "#fff"
				}
			}
		}
	},
	mounted () {

	},
}




</script>

<style></style>
