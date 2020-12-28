<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Alma Deco&Art</title>
  <link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style2.css">
</head>

<body>
  <!-- Banner section -->
  <div class="banner-wrap">
    <h1>ALMA DECO&ART</h1>
    <p>el arte es VIDA </p>
    <a href="https://www.facebook.com/ALMA-Art-Deco-125661414689525"> Facebook </a>  
    
  </div>
   
   <!-- Cards section --> 
  <div class="cards-wrap">
     <h2>Todo lo que buscas en un solo lugar</h2>
    <!-- Cards container -->
    <div class="cards-container">

      <!-- 1 card -->
      <div class="card">
         <img src="https://source.unsplash.com/collection/11504460/200x200">
         <h3>Cuadros</h3>
         <p>Arte Frances, Oleo... </p>
      </div>

      <!-- 2 card -->
      <div class="card">
         <img src="https://source.unsplash.com/collection/2054004/200x200">
         <h3>Relojes</h3>
         <p>De varios estilos</p>
      </div>

      <!-- 3 card -->
      <div class="card">
         <img src="https://source.unsplash.com/collection/3415088/200x200">
         <h3>Decoracion </h3>
         <p>Todo para tu casa</p>
      </div>
    </div>
  </div>

  <!-- Footer section -->
  <footer>
    <p>Website made by DaniBus with the ❤️</p>    
  </footer>
      
    /* Write some CSS below */

body {
	font-family: "LORA", sans-serif;
	margin: 0;
}
.banner-wrap{
	background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url("https://source.unsplash.com/collection/14300463"); 
	background-size: cover;
	background-position: center;
	padding: 150px 0;
	text-align: center;
}
h1{
	color: white ;
	font-size: 45px;
	margin: 0;
	font-weight: bold;
}
p{
	color: rgba(255,255,255,.6);
	font-size: 22px;
}
a{
    background-color: #1A48E3;	
    color: white;
    padding: 14px 30px;
    border-radius:4px;
    text-decoration:underline;	
    transition: .3s;
    font-size:16px;
    font-weight:bold;
    border:none;
}
.cards-wrap{
	width: 860px;
	margin: 60px auto;
}
.cards-container{
	display: flex;
	flex-direction: row;
	align-items: center;
	justify-content: space-between;
}
.card{
	background: white;
	box-shadow: 0 0 10px rgba(0,0,0,0.2);
	border-radius: 4px;
	padding: 24px;
	margin: 8px;
	}

.card img{
	align-items: center;
	width: 200px;
	height: 200px;
}
.card p{
	color: #393939;
	font-size: 15px;
}	
footer{
	background: gray;
	color: white;
	padding: 30px 60px;
	bottom: 0;
	left: 0;
	right: 0;
}
footer p{
	color:white;
	margin: 0;
	font-size: 18px;
	text-align: center;
}
    </div>

</body>
</html>




