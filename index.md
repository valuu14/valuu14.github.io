<!DOCTYPE html>
<html>
<head>
<link rel="icon" href="Pics/icon.png">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" type="text/css" href="style.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link href='http://fonts.googleapis.com/css?family=Cookie' rel='stylesheet' type='text/css'>
<title>Avicii</title>
</head>

<body>

<!-- Navbar start code -->

<nav id="navbar">
  <a href="index.html">Home</a>
  <a href="about.html">About</a>
  <a href="music.html">Music</a>
  <a href="legacy.html">Legacy</a>
  <a href="media.html">Media</a>
</nav>
<section>  
  <a href="index.html" id="nothing"><img src="Pics/Avicii_Logo_White.png"></a>
</section>
<!-- Navbar end code -->

<!-- Auto changing pictures starting code -->

<header class="slideshow-container">

<div class="mySlides fade">
  <img src="Pics/Avicii1.jpg" class="img">
</div>

<div class="mySlides fade">
  <img src="Pics/Avicii2.jpg" class="img">
</div>

<div class="mySlides fade">
  <img src="Pics/Avicii3.jpg" class="img">
</div>

<div class="mySlides fade">
  <img src="Pics/Avicii4.jpg" class="img">
</div>

<div class="mySlides fade">
  <img src="Pics/Avicii5.jpg" class="img">
</div>

<div class="mySlides fade">
  <img src="Pics/Avicii6.jpg" class="img">
</div>

</header>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
</div>

<script>
var slideIndex = 0;
showSlides();

function showSlides() {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 2500);
}
</script>

<!-- Auto changing pictures end code -->

<div>
  <div class="header">
    <h1>Avicii</h1>    
  </div>
<p class="text">"We all reach a point in our lives and careers where we understand what matters the most to us."</p>
</div>

<div>
	<hr>
</div>

<footer>
  <div>
    <img src="Pics/Avicii sign.png" class="signature">
  </div>
	<table class="social">
		<tr>
			<td><a href="https://www.facebook.com/avicii" class="fa fa-facebook" target="_blank"></a></td>
			<td><a href="https://twitter.com/Avicii" class="fa fa-twitter" target="_blank"></a></td>
			<td><a href="https://www.youtube.com/channel/UCPHjpfnnGklkRBBTd0k6aHg" class="fa fa-youtube" target="_blank"></a></td>
			<td><a href="https://www.instagram.com/avicii/?hl=en" class="fa fa-instagram" target="_blank"></a></td>
      <td><a href="https://open.spotify.com/artist/1vCWHaC5f2uS3yhpwWbIA6" class="fa fa-spotify" target="_blank"></a></td>
      <td><a href="https://itunes.apple.com/us/artist/avicii/298496035" class="fa fa-apple"></a></td>
		</tr>
	</table>
  <p>?? 2019 Valentin Molnar. All rights reserved.</p>
</footer>

</body>
</html>
