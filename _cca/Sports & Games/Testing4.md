---
title: Testing4
permalink: /testing4/
variant: markdown
description: ""
third_nav_title: Sports & Games
---
<style>
* {
margin: 0;
padding: 0;
box-sizing: border-box;
}

.slideshow-container {
width: 100%;
max-width: 650px;
margin: auto;
overflow: hidden;
position: relative;
}

.slides {
display: flex;
transition: transform 0.5s ease; /* Smooth transition for sliding */
width: 300%;
}

.slide {
width: 300%; /* Each slide takes up 100% of the container */
height: auto;
}

.slide img {
width: 300%;
height: auto;
object-fit: cover;
cursor: pointer; /* Make the images clickable */
}

/* Control the slide transition when the radio buttons are selected */
#slide1:checked ~ .slides {
transform: translateX(0);
}

#slide2:checked ~ .slides {
transform: translateX(-33%); /* Move to the second slide */
}

#slide3:checked ~ .slides {
transform: translateX(-66%); /* Move to the third slide */
}

/* Disable left arrow when on the first slide */
#slide1:checked ~ .arrow-left {
pointer-events: none;
opacity: 0.3;
}

/* Disable right arrow when on the last slide */
#slide3:checked ~ .arrow-right {
pointer-events: none;
opacity: 0.3;
}
	
/* Mobile Devices (up to 600px) */
@media (min-width: 600px) {
.slide img {
width: 60%;
height: auto;
}
}

.slide img {
width: 100%; /* Ensure the images take up the full container width */
height: auto; /* Maintain aspect ratio */
}
}

@media (max-width: 768px) {
.slide img {
width: 100%;
height: auto;
}
}

@media (min-width: 769px) {
 .slide img {
 width: 80%;
 height: auto;
 }
}
</style>

<div class="slideshow-container">

<input checked="" id="slide1" name="slide" type="radio">
<input id="slide2" name="slide" type="radio">
<input id="slide3" name="slide" type="radio">
<div class="slides">
<label class="slide" for="slide2">
<img alt="Image 1" src="/images/School_Information.png">
</label>
<label class="slide" for="slide3">
<img alt="Image 2" src="/images/Primary_2_resize_.png">
</label>
<label class="slide" for="slide1">
<img alt="Image 3" src="/images/School_Ethos_.jpg">
</label>
</div>
</div>