<li><a href="https://pythontutor.com/render.html#mode=display/"> python </a></li>


<li><a href="https://jsitor.com/">анимация</a></li>



<!doctype html><html><head></head><body><!doctype html>
<html>

<head></head>

<body>
	<p style="text-align: center">

		<button>Покорми меня!</button>
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
alert("НЕ ТРОГАЙ МОИ ПЕЛЬМЕНИ!!!!");
});

document.getElementById('myImg').onclick = myFunction;

function myFunction() {
  alert('Ouch!!!');
}

requestAnimationFrame(animate);





		</script>
		<script type="text/javascript">
  <p>для того чтобы создать анимацию нам нужно:
	  
	1.мозги
 2.компьютер(желательно рабочий)
 3.Приступим
 </p>
 
 <img id="myImg" src="https://github.com/rostoSonya/-1/assets/153977631/7a3bc38a-4e50-43e1-afba-18c7267ca263" style="position: relative">









  


                                    
