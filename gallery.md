---
title: Hall of Fame
layout: default
description: Heroes get remembered, but legends never die
---
> Remember kid, there's heroes and there's legends. Heroes get remembered but legends never die...

The Sandlot
<!-- HTML -->

<!-- Slideshow container -->
<div class="slideshow-container">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides fade">
    <img src="assets/history/2009.png" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="assets/history/2010.png" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="assets/history/2011.png" style="width:100%">
  </div>

    <div class="mySlides fade">
    <img src="assets/history/2012.png" style="width:100%">
  </div>

    <div class="mySlides fade">
    <img src="assets/history/2013.png" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="assets/history/2014.png" style="width:100%">
  </div>

    <div class="mySlides fade">
    <img src="assets/history/2015.png" style="width:100%">
  </div>

    <div class="mySlides fade">
    <img src="assets/history/2016.png" style="width:100%">
  </div>

    <div class="mySlides fade">
    <img src="assets/history/2017.png" style="width:100%">
  </div>

    <div class="mySlides fade">
    <img src="assets/history/2018.png" style="width:100%">
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>

<!-- The dots/circles -->
<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span>
  <span class="dot" onclick="currentSlide(4)"></span>
  <span class="dot" onclick="currentSlide(5)"></span> 
  <span class="dot" onclick="currentSlide(6)"></span> 
  <span class="dot" onclick="currentSlide(7)"></span> 
  <span class="dot" onclick="currentSlide(8)"></span>
  <span class="dot" onclick="currentSlide(9)"></span>
  <span class="dot" onclick="currentSlide(10)"></span> 
</div>

<!-- CSS -->
<style>
* {box-sizing:border-box}

/* I added this to try and center any tables */
table.center {
  margin-left:auto; 
  margin-right:auto;
}


/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Hide the images by default */
.mySlides {
  display: none;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 40%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
  background-color: #145998;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
  opacity: 0.2;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  background-color: #145998;
  color: white;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
  opacity: 0.7;
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

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.round {
  border-radius: 50%;
}

.active, .dot:hover {
  background-color: #145998;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

</style>

<script>
var slideIndex = 1;
showSlides(slideIndex);

// Next/previous controls
function plusSlides(n) {
  showSlides(slideIndex += n);
}

// Thumbnail image controls
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
___
<table style="width: auto; height: auto; margin-left: auto; margin-right: auto;" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;"><strong>Owner</strong></span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;"><strong># Seasons</strong></span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;"><strong>Record</strong></span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;"><strong>Win %</strong></span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">Katie Beth</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">1</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">9 - 4</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">69.2</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">Jonathan</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">10</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">81 - 49</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">62.3</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">Jeremy</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">5</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">40 - 25</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">61.5</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">Davis</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">10</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">77 - 52 - 1</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">59.2</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">David</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">10</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">70 - 60</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">53.8</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">Paul</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">5</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">34 - 31</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">52.3</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">Rob</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">9</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">55 - 61 - 1</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">47.0</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">Daniel</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">10</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">53 - 75 - 2</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">40.8</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">Joel</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">7</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">37 - 54</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">40.7</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">Jeff/Liz</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">5</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">26 - 39</span></p>
</td>
<td valign="top">
<p><span style="color: #000000; font-family: Arial; font-size: large;">40.0</span></p>
</td>
</tr>
</tbody>
</table>