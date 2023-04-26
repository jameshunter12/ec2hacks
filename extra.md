<html>
    <head>
    <link rel="stylesheet" href="extra.css">
    </head>
    <body>
<div class="index-header">
    <h1>Extra Seed</h1>
    <p>Add an element of bootstrap to this page (ex. carousel) OR Add an element using Tailwind</p>
</div>

<div class="slideshow-container fade">

  <!-- Full images with numbers and message Info -->
  <div class="Containers">
    <div class="MessageInfo">1 / 3</div>
    <img src="panda.jpg" style="width:100%">
    <div class="Info">First caption</div>
  </div>

  <div class="Containers">
    <div class="MessageInfo">2 / 3</div>
    <img src="james.jpg" style="width:100%">
    <div class="Info">Second Caption</div>
  </div>

  <div class="Containers">
    <div class="MessageInfo">3 / 3</div>
    <img src="score.jpg" style="width:100%">
    <div class="Info">Third Caption</div>
  </div>

  <!-- Back and forward buttons -->
  <a class="Back" onclick="plusSlides(-1)">&#10094;</a>
  <a class="forward" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>

<!-- The circles/dots -->
<div style="text-align:center">
  <span class="dots" onclick="currentSlide(1)"></span>
  <span class="dots" onclick="currentSlide(2)"></span>
  <span class="dots" onclick="currentSlide(3)"></span>
</div> 
