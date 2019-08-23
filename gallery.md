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


.tg  {border-collapse:collapse;width:100%;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:0px;overflow:hidden;word-break:normal;border-color:#ccc;color:#333;background-color:#fff;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:0px;overflow:hidden;word-break:normal;border-color:#ccc;color:#333;background-color:#f0f0f0;}
.tg .tg-qtxd{background-color:#f9f9f9;font-size:18px;border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-1kv1{font-size:18px;background-color:#58729a;color:#ffffff;border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-cyr5{background-color:#f9f9f9;font-size:18px;border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-fuxe{font-size:18px;border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-7jts{font-size:18px;border-color:inherit;text-align:center;vertical-align:top}
tr:hover {background-color:#f5f5f5;}

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

<table class="tg">
  <tr>
    <th class="tg-1kv1">Owner</th>
    <th class="tg-1kv1"># Seasons</th>
    <th class="tg-1kv1">Record</th>
    <th class="tg-1kv1">Win %</th>
  </tr>
  <tr>
    <td class="tg-cyr5">Katie Beth</td>
    <td class="tg-qtxd">1</td>
    <td class="tg-qtxd">9 - 4</td>
    <td class="tg-qtxd">69.2</td>
  </tr>
  <tr>
    <td class="tg-fuxe">Jonathan</td>
    <td class="tg-7jts">10</td>
    <td class="tg-7jts">81 - 49</td>
    <td class="tg-7jts">62.3</td>
  </tr>
  <tr>
    <td class="tg-cyr5">Jeremy</td>
    <td class="tg-qtxd">5</td>
    <td class="tg-qtxd">40 - 25</td>
    <td class="tg-qtxd">61.5</td>
  </tr>
  <tr>
    <td class="tg-fuxe">Davis</td>
    <td class="tg-7jts">10</td>
    <td class="tg-7jts">77 - 52 - 1</td>
    <td class="tg-7jts">59.2</td>
  </tr>
  <tr>
    <td class="tg-cyr5">David</td>
    <td class="tg-qtxd">10</td>
    <td class="tg-qtxd">70 - 60</td>
    <td class="tg-qtxd">53.8</td>
  </tr>
  <tr>
    <td class="tg-fuxe">Paul</td>
    <td class="tg-7jts">5</td>
    <td class="tg-7jts">34 - 31</td>
    <td class="tg-7jts">52.3</td>
  </tr>
  <tr>
    <td class="tg-cyr5">Rob</td>
    <td class="tg-qtxd">9</td>
    <td class="tg-qtxd">55 - 61 - 1</td>
    <td class="tg-qtxd">47.0</td>
  </tr>
  <tr>
    <td class="tg-fuxe">Daniel</td>
    <td class="tg-7jts">10</td>
    <td class="tg-7jts">53 - 75 - 2</td>
    <td class="tg-7jts">40.8</td>
  </tr>
  <tr>
    <td class="tg-cyr5">Joel</td>
    <td class="tg-qtxd">7</td>
    <td class="tg-qtxd">37 - 54</td>
    <td class="tg-qtxd">40.7</td>
  </tr>
  <tr>
    <td class="tg-fuxe">Jeff/Liz</td>
    <td class="tg-7jts">5</td>
    <td class="tg-7jts">26 - 39</td>
    <td class="tg-7jts">40.0</td>
  </tr>
</table>