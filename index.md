<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title>youku</title>
		<style>
			p {
				background-color: red;
				font-size: 50px;	
				color: white;			
			}
			.lj {
				animation: lj 3s linear infinite;				
			}
			.qx {
				animation: qx 4s linear infinite;					
			}
			/*@keyframes lj {
				0% {opacity: 100%}
				50% {opacity: 100%}
				100% {opacity: 0}
			}*/
			@keyframes qx {
				0% {opacity: 0}
			    50%{opacity: 100%}
				100% {opacity: 0}
			}
			
		</style>
	</head>
	<body>
		<div>
			<audio src="img/北京欢迎你.mp3" controls="controls"></audio>
		</div>
		<p class="lj">迎接另一个晨曦带来全新空气</p>
		<p class="qx">气息改变情味不变茶香飘满情谊</p>
		
	</body>
</html>
