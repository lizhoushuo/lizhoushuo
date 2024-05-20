<template>
	<div
		style="position: fixed;top: 440px;left: 45px;width: 460px;height: 350px;border-radius: 10px;border: 3px solid #43544c;background-color: rgba(0, 0, 0, .5);">
		<div style="border-bottom: 2px solid #43544c;height: 50px;display: flex;align-items: center;">
			<img src="../assets/image/容器 47@2x.png" alt="" style="margin-left: 20px;">
			<p style="font-size: 20px;color: #a3b9af;font-weight: 800;margin-left: 10px;font-family: SimSun;">
				天气预报</p>
		</div>
		<div style="width: 100%;font-size: 14px;display: flex;align-items: center;justify-content: space-around	;margin-top: 15px;">
			<div style="color: #9dbeb0;font-size: 14px;">
				<p>
					<span>今天</span>
					<span style="margin-left: 10px;">03/11</span>
				</p>
			</div>
			<div style="display: flex;align-items: center;">
         <img src="../assets/image/83@2x.png" alt="" style="width: 25px;height: 25px;">
				 <span style="color: #c8a328;margin-left: 10px;font-size: 14px;">晴</span>
			</div>
			<div style="color: #9dbeb0;display: flex;align-items: center;">
        <span>18℃</span>
				<div style="width: 100px;height: 10px;border-radius: 10px;background-color: #1e4234;margin: 0 10px;">
					<div style="width: 38%;height: 100%;background-color: #dbcd7b;border-radius: 10px;margin: auto;"></div>
				</div>
				<span>24℃</span>
			</div>
		</div>
		<div style="width: 100%;font-size: 14px;display: flex;align-items: center;justify-content: space-around	;margin-top: 15px;">
			<div style="color: #9dbeb0;font-size: 14px;">
				<p>
					<span>明天</span>
					<span style="margin-left: 10px;">03/12</span>
				</p>
			</div>
			<div style="display: flex;align-items: center;">
         <img src="../assets/image/83@2x.png" alt="" style="width: 25px;height: 25px;">
				 <span style="color: #c8a328;margin-left: 10px;font-size: 14px;">晴</span>
			</div>
			<div style="color: #9dbeb0;display: flex;align-items: center;">
        <span>12℃</span>
				<div style="width: 100px;height: 10px;border-radius: 10px;background-color: #1e4234;margin: 0 10px;">
					<div style="width: 70%;height: 100%;background-color: #dbcd7b;border-radius: 10px;margin: auto;"></div>
				</div>
				<span>30℃</span>
			</div>
		</div>
		<div style="width: 100%;font-size: 14px;display: flex;align-items: center;justify-content: space-around	;margin-top: 15px;">
			<div style="color: #9dbeb0;font-size: 14px;">
				<p>
					<span>周三</span>
					<span style="margin-left: 10px;">03/13</span>
				</p>
			</div>
			<div style="display: flex;align-items: center;">
         <img src="../assets/image/83@2x.png" alt="" style="width: 25px;height: 25px;">
				 <span style="color: #c8a328;margin-left: 10px;font-size: 14px;">晴</span>
			</div>
			<div style="color: #9dbeb0;display: flex;align-items: center;">
        <span>16℃</span>
				<div style="width: 100px;height: 10px;border-radius: 10px;background-color: #1e4234;margin: 0 10px;">
					<div style="width: 60%;height: 100%;background-color: #dbcd7b;border-radius: 10px;margin-left: 30px;"></div>
				</div>
				<span>32℃</span>
			</div>
		</div>
		<div style="width: 100%;font-size: 14px;display: flex;align-items: center;justify-content: space-around	;margin-top: 15px;">
			<div style="color: #9dbeb0;font-size: 14px;">
				<p>
					<span>周四</span>
					<span style="margin-left: 10px;">03/14</span>
				</p>
			</div>
			<div style="display: flex;align-items: center;">
         <img src="../assets/image/83@2x.png" alt="" style="width: 25px;height: 25px;">
				 <span style="color: #c8a328;margin-left: 10px;font-size: 14px;">晴</span>
			</div>
			<div style="color: #9dbeb0;display: flex;align-items: center;">
        <span>12℃</span>
				<div style="width: 100px;height: 10px;border-radius: 10px;background-color: #1e4234;margin: 0 10px;">
					<div style="width: 55%;height: 100%;background-color: #dbcd7b;border-radius: 10px;margin-left: 30px"></div>
				</div>
				<span>32℃</span>
			</div>
		</div>
		<div style="width: 100%;font-size: 14px;display: flex;align-items: center;justify-content: space-around	;margin-top: 15px;">
			<div style="color: #9dbeb0;font-size: 14px;">
				<p>
					<span>周五</span>
					<span style="margin-left: 10px;">03/15</span>
				</p>
			</div>
			<div style="display: flex;align-items: center;">
         <img src="../assets/image/83@2x.png" alt="" style="width: 25px;height: 25px;">
				 <span style="color: #c8a328;margin-left: 10px;font-size: 14px;">晴</span>
			</div>
			<div style="color: #9dbeb0;display: flex;align-items: center;">
        <span>13℃</span>
				<div style="width: 100px;height: 10px;border-radius: 10px;background-color: #1e4234;margin: 0 10px;">
					<div style="width: 38%;height: 100%;background-color: #dbcd7b;border-radius: 10px;margin-left: 15px;"></div>
				</div>
				<span>18℃</span>
			</div>
		</div>
		<div style="width: 100%;font-size: 14px;display: flex;align-items: center;justify-content: space-around	;margin-top: 15px;">
			<div style="color: #9dbeb0;font-size: 14px;">
				<p>
					<span>周六</span>
					<span style="margin-left: 10px;">03/11</span>
				</p>
			</div>
			<div style="display: flex;align-items: center;">
         <img src="../assets/image/83@2x.png" alt="" style="width: 25px;height: 25px;">
				 <span style="color: #c8a328;margin-left: 10px;font-size: 14px;">晴</span>
			</div>
			<div style="color: #9dbeb0;display: flex;align-items: center;">
        <span>15℃</span>
				<div style="width: 100px;height: 10px;border-radius: 10px;background-color: #1e4234;margin: 0 10px;">
					<div style="width: 50%;height: 100%;background-color: #dbcd7b;border-radius: 10px;margin-left: 30px;"></div>
				</div>
				<span>28℃</span>
			</div>
		</div>
		<div style="width: 100%;font-size: 14px;display: flex;align-items: center;justify-content: space-around	;margin-top: 15px;">
			<div style="color: #9dbeb0;font-size: 14px;">
				<p>
					<span>周日</span>
					<span style="margin-left: 10px;">03/11</span>
				</p>
			</div>
			<div style="display: flex;align-items: center;">
         <img src="../assets/image/83@2x.png" alt="" style="width: 25px;height: 25px;">
				 <span style="color: #c8a328;margin-left: 10px;font-size: 14px;">晴</span>
			</div>
			<div style="color: #9dbeb0;display: flex;align-items: center;">
        <span>18℃</span>
				<div style="width: 100px;height: 10px;border-radius: 10px;background-color: #1e4234;margin: 0 10px;">
					<div style="width: 38%;height: 100%;background-color: #dbcd7b;border-radius: 10px;margin-left: 15px;"></div>
				</div>
				<span>20℃</span>
			</div>
		</div>
	</div>
</template>
<script>

</script>
