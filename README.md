<li><a href="https://pythontutor.com/render.html#mode=display/"> python </a></li>


<li><a href="https://jsitor.com/">анимация</a></li>



<html>

<head></head>

<body>
	<p style="text-align: center">

		<button>ПЕЛЬМЕШКИ!</button>
		<p>Горошка и морковки хватит, МММ... салатик. МММ... отлично...МММ... салатик</p>

		<style>
			body {
				height: 200px;
				background: beige;
			}

			.dot {
				height: 8px;
				width: 8px;
				border-radius: 4px;
				/* скруглённые углы */
				background: blue;
				position: absolute;
			}

			#myImg {
				height: 250px;
			}
		</style>



		<img id="myImg" src="https://meat-expert.ru/files/uploads/obzor/_2023/30/01.jpg" style="position: relative">

</p>
		<script>
			var cat = document.querySelector("img");
var angle = 0, lastTime = null;
function animate(time) {
if (lastTime != null)
angle += (time - lastTime) * 0.002;
lastTime = time;
cat.style.top = (Math.cos(angle) * 50      ) + "px";
cat.style.left = (Math.sin(angle) * 200) + "px";
requestAnimationFrame(animate);
}

var button = document.querySelector("button");
button.addEventListener("click", function() {
alert("OUCH!!!!");
});

document.getElementById('myImg').onclick = myFunction;

function myFunction() {
  alert('НЕ ТРОГАЙ МОИ ПЕЛЬМЕНИ!!!');
}


requestAnimationFrame(animate);





		</script>
		<script type="text/javascript">





		</script>



  <img id="img" src="https://derpicdn.net/img/2017/10/10/1557772/full.gif" style="position: relative" width="300">
		<script>
			var cat1= document.querySelector("img");
var angle = 0, lastTime = null;
function animate1(time) {
if (lastTime != null)
angle += (time - lastTime) * 0.050;
lastTime = time;
cat.style.top = (Math.cos(angle) * 500      ) + "px";
cat.style.left = (Math.sin(angle) * 200) + "px";
requestAnimationFrame(animate1);
}

var button = document.querySelector("button");
button.addEventListener("click", function() {
alert("НЕ ТРОГАЙ МОИ ПЕЛЬМЕНИ!!!!");
});

document.getElementById('img').onclick = myFunction;

function myFunction() {
  alert('Ouch!!!');
}


requestAnimationFrame(animate1);





		</script>
		<script type="text/javascript">



<li><a href="https://jsitor.com/">анимация</a></li>

		</script>
</body>
</html>



                                    
