<template>
	<dv-full-screen-container>
		<dv-border-box-6 class="a">
			<img src="../assets/image/标题.png" alt="" style="width: 100%;position: fixed;" />
			<bxgjd />
			<tqyb />
			<dkdt />
			<qwe />
			<top />
			<trfl />
			<scxq />
			<topright />
			<jdyj />
			<bch />
			<trSq />
		</dv-border-box-6>
	</dv-full-screen-container>
</template>

<script>
import qwe from '@/components/Dt.vue'
import bxgjd from "@/components/BxgJd.vue"
import tqyb from "@/components/TqYb.vue"
import dkdt from "@/components/DkDt.vue"
import top from "@/components/Top.vue"
import trfl from "@/components/TrFl.vue"
import scxq from "@/components/CdXq.vue"
import topright from "@/components/TopRight.vue"
import jdyj from "@/components/JdYj.vue"
import bch from "@/components/Bch.vue"
import trSq from "@/components/TrSq.vue"
export default {
	components: { bxgjd, tqyb, dkdt, qwe, top, trfl, scxq, topright, jdyj, bch, trSq },
	data () {
		return {
			flag: false,
			a: false,
			b: true,
			toggleTheme: false,
			isShowDarkTheme: "",
		}
	},
	methods: {
		fullScreen () {
			this.b = !this.b
			let full = document.fullscreenElement;
			if (!full) {
				// 文档根节点的方法requestFullscreen（）实现全屏模式
				document.documentElement.requestFullscreen();
			} else {
				// 文档根节点的方法exitFullscreen（）退出全屏
				document.exitFullscreen()
			}
		},
	},
	created() {
		this.fullScreen()
	},
}
</script>
<style>
* {
	margin: 0;
	padding: 0;
}

.a {
	background-image: url(../assets/image/bg\(1\).png);
	background-size: 100% 100%;
	background-repeat: no-repeat;
	background-position: center;
	height: 100%;
	width: 100%;
	background-color: #0d1d17;
	border: 1px solid #ccc;
	position: fixed;
	z-index: -10;
}
</style>
