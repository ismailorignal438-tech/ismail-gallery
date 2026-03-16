<!DOCTYPE html>
<html>
<head>
<title>Ismail Khan Gallery</title>

<style>

body{
margin:0;
font-family:Arial;
background:#f4f4f4;
}

header{
background:#1877f2;
color:white;
padding:15px;
text-align:center;
font-size:25px;
}

.container{
padding:20px;
}

h2{
text-align:center;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit, minmax(200px,1fr));
gap:15px;
}

.gallery img{
width:100%;
border-radius:10px;
transition:0.3s;
}

.gallery img:hover{
transform:scale(1.05);
}

.video{
display:flex;
justify-content:center;
gap:20px;
flex-wrap:wrap;
margin-top:20px;
}

video{
width:300px;
border-radius:10px;
}

footer{
margin-top:30px;
background:#222;
color:white;
text-align:center;
padding:10px;
}

</style>

</head>

<body>

<header>
Ismail Khan Photo & Video Collection
</header>

<div class="container">

<h2>My Photos</h2>

<div class="gallery">
<img src="photo1.jpg">
<img src="photo2.jpg">
<img src="photo3.jpg">
<img src="photo4.jpg">
</div>

<h2>My Videos</h2>

<div class="video">
<video controls>
<source src="video1.mp4" type="video/mp4">
</video>

<video controls>
<source src="video2.mp4" type="video/mp4">
</video>
</div>

</div>

<footer>
FB: Ismail Khan
</footer>

</body>
</html>
