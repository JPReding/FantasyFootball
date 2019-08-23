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

#### Overall Regular Season Records
___

<style>
  table.center {
    margin-left:auto; 
    margin-right:auto;
  }
</style>

<table class="wdn_responsive_table center" id="t556943"><caption>Overall Regular Season Records</caption><thead> <tr> <th colspan="1" id="t556943_row_0col_0">Owner</th> <th colspan="1" id="t556943_row_0col_1"># Seasons</th> <th colspan="1" id="t556943_row_0col_2">Record</th> <th colspan="1" id="t556943_row_0col_3">Win %</th> </tr></thead><tbody> <tr> <td colspan="1" headers="t556943_row_0col_0" data-header="Owner">Katie Beth</td> <td colspan="1" headers="t556943_row_0col_1" data-header="# Seasons">1</td> <td colspan="1" headers="t556943_row_0col_2" data-header="Record">9 - 4</td> <td colspan="1" headers="t556943_row_0col_3" data-header="Win %">69.2</td> </tr> <tr> <td colspan="1" headers="t556943_row_0col_0" data-header="Owner">Jonathan</td> <td colspan="1" headers="t556943_row_0col_1" data-header="# Seasons">10</td> <td colspan="1" headers="t556943_row_0col_2" data-header="Record">81 - 49</td> <td colspan="1" headers="t556943_row_0col_3" data-header="Win %">62.3</td> </tr> <tr> <td colspan="1" headers="t556943_row_0col_0" data-header="Owner">Jeremy</td> <td colspan="1" headers="t556943_row_0col_1" data-header="# Seasons">5</td> <td colspan="1" headers="t556943_row_0col_2" data-header="Record">40 - 25</td> <td colspan="1" headers="t556943_row_0col_3" data-header="Win %">61.5</td> </tr> <tr> <td colspan="1" headers="t556943_row_0col_0" data-header="Owner">Davis</td> <td colspan="1" headers="t556943_row_0col_1" data-header="# Seasons">10</td> <td colspan="1" headers="t556943_row_0col_2" data-header="Record">77 - 52 - 1</td> <td colspan="1" headers="t556943_row_0col_3" data-header="Win %">59.2</td> </tr> <tr> <td colspan="1" headers="t556943_row_0col_0" data-header="Owner">David</td> <td colspan="1" headers="t556943_row_0col_1" data-header="# Seasons">10</td> <td colspan="1" headers="t556943_row_0col_2" data-header="Record">70 - 60</td> <td colspan="1" headers="t556943_row_0col_3" data-header="Win %">53.8</td> </tr> <tr> <td colspan="1" headers="t556943_row_0col_0" data-header="Owner">Paul</td> <td colspan="1" headers="t556943_row_0col_1" data-header="# Seasons">5</td> <td colspan="1" headers="t556943_row_0col_2" data-header="Record">34 - 31</td> <td colspan="1" headers="t556943_row_0col_3" data-header="Win %">52.3</td> </tr> <tr> <td colspan="1" headers="t556943_row_0col_0" data-header="Owner">Rob</td> <td colspan="1" headers="t556943_row_0col_1" data-header="# Seasons">9</td> <td colspan="1" headers="t556943_row_0col_2" data-header="Record">55 - 61 - 1</td> <td colspan="1" headers="t556943_row_0col_3" data-header="Win %">47.0</td> </tr> <tr> <td colspan="1" headers="t556943_row_0col_0" data-header="Owner">Daniel</td> <td colspan="1" headers="t556943_row_0col_1" data-header="# Seasons">10</td> <td colspan="1" headers="t556943_row_0col_2" data-header="Record">53 - 75 - 2</td> <td colspan="1" headers="t556943_row_0col_3" data-header="Win %">40.8</td> </tr> <tr> <td colspan="1" headers="t556943_row_0col_0" data-header="Owner">Joel</td> <td colspan="1" headers="t556943_row_0col_1" data-header="# Seasons">7</td> <td colspan="1" headers="t556943_row_0col_2" data-header="Record">37 - 54</td> <td colspan="1" headers="t556943_row_0col_3" data-header="Win %">40.7</td> </tr> <tr> <td colspan="1" headers="t556943_row_0col_0" data-header="Owner">Jeff/Liz</td> <td colspan="1" headers="t556943_row_0col_1" data-header="# Seasons">5</td> <td colspan="1" headers="t556943_row_0col_2" data-header="Record">26 - 39</td> <td colspan="1" headers="t556943_row_0col_3" data-header="Win %">40.0</td> </tr></tbody></table>