<!DOCTYPE html>

<html lang="es">
 
	<head>
		<meta charset='utf-8'>
		<link rel="stylesheet" href="stylesheet.css">
		<script src="http://code.jquery.com/jquery-1.7.1.min.js"></script>
		<script src="scriptprincipal.js"></script>
		<style>
      video {
        width: 200px;
        height: 112px;
        border: 1px solid black;
      }
      
      .video-container {
        display: inline-block;
        text-align: center;
      }
      
      p {
        font: 14px Arial;
      }
    </style>




	</head>
	 
     
  
	<body>
  
	<canvas id="myCanvas" width="800" height="200" ></canvas>
	
	
		
		<div id='contenido'>
			<header>
				<!-- <hgroup>
					<h1>ya mismo lo usamos</h1>
					
				</hgroup> -->
				<nav>
					<ul>
						<li><a href='/Biblioteca/index.html'>INICIO</a></li>
						<li><a href='registro-login.html'>LOGIN</a></li>
					</ul>
				</nav>
			</header>
			<section>
			
				<div id='textPr'>
					<article>
						<hgroup>
							<h1>Bienvenidos a Nuestra Página Web</h1>
						</hgroup>
						<p> 
						Somos una tienda online de ropa para hombre, mujer, niños, calzado y complementos.
						Aprovecha nuestras últimas rebajas en ropa. También tenemos
						liquidación de stock para tiendas. 
											
						
						</p>
					</article>
					<br>
					<div>
						<IMG SRC="ropa-mintmelon.jpg" align="right" >
						</div>
						<div>
					<div>
					<aside>
							<button style='width:210px; height:50px'>
								<b>  Ropa pada ninos  </b>
								<br>
							</button>
								<br>
							<button style='width:210px; height:50px'>
								<b> Ropa para ninas  </b>
								<br>
							</button>
								<br>
							<button style='width:210px; height:50px'>
								<b> Ropa para damas  </b>
								<br>
							</button>
								<br>
							<button style='width:210px; height:50px'>
								<b>Ropa para caballeros</b>
								<br>
							</button>
								<br>
							<button style='width:210px; height:50px'>
								<b>Accesorios para damas</b>
								<br>
							</button>
								<br>
							<button style='width:210px; height:50px'>
								<b>Accesorios para caballeros</b>
								<br>
							</button>
								
						
					</aside>
					
						
						<br>
						<br>
						<br>
						<br>
						<video  autoplay="autoplay" loop="loop" muted="muted"  >
		
							<source src="Lightmirror - Videos para Fondos HD .wmv.mp4" type='video/mp4' />
						</video>
						
						<hgroup>
							<h>Visita nuestro <a href='http://www.youtube.com/'>Canal de Youtube</a></h5>
						</hgroup> 
						
						
						<br>
						<br>
					<div style="overflow:hidden; width:960px; margin:100 auto; padding:0 20px;"> 
                
					</div>
				</div>
			</section>
		</div>
		<footer>
			
			<style>

	body {
		margin:0px;
		padding: 0px;
	}
		
				</style>
				<script>
				context.beginPath();
				context.moveTo(x,y);
	
				context.font = 'italic 40px Calibri';
				</script>
				<script>

	
				window.onload = function() {
				var canvas = document.getElementById("myCanvas");
				var context = canvas.getContext("2d");
				var x = 300;
				var y = 150;
 
				context.font = "60pt Calibri";
				context.lineWidth = 4;

				context.strokeStyle = "pink";
				context.strokeText("Ventas Online", x, y);
			};
	
			</script>
			</canvas>
		</footer>	
	 
	 
	</body>
	
	
	<audio src="Pra Voc.mp3" preload="auto" controls> </audio>
</html>
