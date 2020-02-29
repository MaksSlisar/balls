<head>
<title>

</title>

<style>
body{
margin:0px;
}
 #canvas{
 border:1px solid;
 }
</style>


</head>
<body>
	<canvas id="canvas" width='800px' height='800px'></canvas>
	
	<script>
	 var balls = [];
	 function Ball() {
	 this.stepX = 10;
	 this.stepY= 10;
	 this.color = "black";
	 this.radius = 35;
	 this.x = 0;
	 this.y = 0;
	}
	var canvas = document.getElementById("canvas");
	var ctx = canvas.getContext("2d");
	canvas.addEventListener('mousedown',createBall);
	setInterval(move,40);

	 
	
	 function createBall(e) {
	 if(!deathball(e)){ 
	 var round = new Ball();
	 round.stepX =  getRandom(-10,10);
	 round.stepY=  getRandom(-10,10);
	 round.radius= getRandom(10,30);
	 round.color = getColor();
	 round.y=e.pageY-canvas.offsetTop;
	 round.x=e.pageX-canvas.offsetLeft;
	 balls.push(round);
	}else{
	
	
	} 
	}
	function move(){
	ctx.clearRect(0, 0,800,800);
	
	
	for (var i = 0;i<balls.length;i++ ){
	
	
		for (var j = i+1;j<balls.length-1;j++ ){
		colision (balls[i], balls[j]);
		}
	
	
	}
	
	
	
	for (var i = 0;i<balls.length;i++){
		
	  
		if(balls[i].x==0){
		
		}else if(balls[i].x+balls[i].radius>800 || balls[i].x-balls[i].radius<0 ){
		balls[i].stepX*=-1;
		balls[i].x+=balls[i].stepX;
		
		}else if (balls[i].y+balls[i].radius>
		800 || balls[i].y-balls[i].radius<0){
		balls[i].stepY*=-1;
		balls[i].y+=balls[i].stepY;
		}else{
		 balls[i].x+=balls[i].stepX;
		 balls[i].y+=balls[i].stepY;
		 draw(balls[i]);
		}
	}
	}
	function draw(round) {
	 ctx.beginPath();
	 ctx.fillStyle = round.color;
     ctx.arc(round.x,round.y,round.radius,0,Math.PI*2,true);
	 ctx.closePath();
	 ctx.fill();
	}
	function getRandom(min, max) {
    return Math.random() * (max - min) + min;
	}
	function getColor(){
	 var color = "#";
	 color+= Math.floor(getRandom(0,255),0);
	 color+= Math.floor(getRandom(0,255),0);
	 color+= Math.floor(getRandom(0,255),0);
	return color;
	}
	function colision(a, b) {
	var katet1 = Math.abs(a.x+a.stepX - b.x+b.stepX);
	var katet2 = Math.abs(a.y+a.stepY - b.y+b.stepY);
	var hipotenyza = Math.sqrt(katet1*katet1 + katet2*katet2);
	 if(hipotenyza<a.radius + b.radius){
	    a.stepX*=-1;
		a.stepY*=-1;
		b.stepX*=-1;
	    b.stepY*=-1;
	 }
	}
	function deathball(e){
	for (var i = 0;i<balls.length;i++ ){
	
	
		
		var katet1 = Math.abs(e.pageX-canvas.offsetLeft - balls[i].x);
		var katet2 = Math.abs(e.pageY-canvas.offsetTop - balls[i].y);
	
	var hipotenyza = Math.sqrt(katet1*katet1 + katet2*katet2);
	 if(hipotenyza<balls[i].radius){
	  balls.splice(i, i);
	  
	   return true;
		
	
	
	}
	 }
	   return false;
	
	}
	
	
	
	
	
	
	
	
	
	
	</script>
</body>	