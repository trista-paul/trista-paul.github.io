<html>
<head>
 
<a href= "https://trista-paul.github.io/">Home</a> | <a href= "https://trista-paul.github.io/projects">Projects</a><br>
<hr>
  
  
  
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box;}
body {font-family: Verdana, sans-serif;}
.mySlides {display: none;}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  maxwidth: 100px;
  maxheight:100px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.4);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* Text box */
#grad1 {
  height: 75px;
  background-color: black; /* For browsers that do not support gradients */
  background-image: linear-gradient(to bottom right, black, white); /* Standard syntax (must be last) */
}

/* The dots/bullets/indicators */
.dot {
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 2s;
  animation-name: fade;
  animation-duration: 2s;
}

@-webkit-keyframes fade {
  from {opacity: 0} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: 0} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .text {font-size: 11px}
}
</style>
</head>
<body>

<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 4</div>
  <img src="project7.png" style="width:100%">
  <div id="grad1"></div>
   <div class="text">From <a href = "https://medium.com/@tristap98/movie-night-coming-up-analysis-of-imdb-ratings-7f290cac2e7f">Analysis of Bad IMDb Ratings</a></div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 4</div>
  <img src="Week4%203.png" style="width:100%">
  <div id="grad1"></div>
  <div class="text"> From <a href = "https://colab.research.google.com/drive/1-isexPVhAmChlHJ6efcOVtzTgxEfpmFs">Intro to Bayes Notebook</a></div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 4</div>
  <img src="project6.png" style="width:100%">
  <div id="grad1"></div>
  <div class="text"> From <a href = "https://medium.com/@tristap98/movie-night-coming-up-analysis-of-imdb-ratings-7f290cac2e7f">Analysis of Bad IMDb Ratings</a></div>
</div>

<div class="mySlides fade">
  <div class="numbertext">4 / 4</div>
  <img src="IMG_1411%20(2).JPG" style="width:100%">
  <div id="grad1"></div>
  <div class="text">Portrait of the Artist as a Young Data Scienttist</div>
</div>

<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span>
</div>

<script>
  
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}

</script>

I'm a junior data scientist located in SF, working on certification with Lambda school. I specialize in analysis, visualization and breaking down the world of data to the corporate audience. You can follow
updates to this portfolio on my Twitter and Github.<br>
<br>
<hr>
Email: <a href= "mailto:TristaGPaul@protonmail.com"></a>TristaGPaul@protonmail.com<br>
Github.io: <a href = "https://github.com/trista-paul">trista-paul</a><br>
Medium: <a href="https://medium.com/@tristap98">Trista G. Paul</a><br>
Twitter: <a href="https://twitter.com/TristaGPaul">@TristaGPaul</a><br>
Linkedin: <a hrer="https://www.linkedin.com/in/trista-g-paul-29131217b/">Trista G Paul<br>
