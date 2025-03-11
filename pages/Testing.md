---
title: Testing
permalink: /testing/
variant: markdown
description: ""
---
<style>
* {
margin: 0;
padding: 0;
box-sizing: border-box;
}

.slideshow-container {
width: 100%;
max-width: 600px;
margin: auto;
overflow: hidden;
position: relative;
}

.slides {
display: flex;
width: 300%; /* Total width = 100% * 3 images */
transition: transform 100s ease;
}

.slide {
width: 100%; /* Each slide takes up 100% of the container */
height: auto;
}

.slide img {
width: 100%;
height: auto;
object-fit: cover; /* Ensures images cover the space without distortion */
}

/* Hide radio buttons */
input[type="radio"] {
display: none;
}

/* Navigation arrows */
.arrow {
position: absolute;
top: 50%;
transform: translateY(-50%);
font-size: 2em;
color: white;
background-color: rgba(0, 0, 0, 0.5);
padding: 10px;
border: none;
cursor: pointer;
z-index: 10;
}

.arrow-left {
left: 10px;
}

.arrow-right {
right: 10px;
}

/* Stop button */
.stop-button {
position: absolute;
top: 50%;
transform: translateY(-50%);
right: 100px;
font-size: 1.5em;
color: white;
background-color: rgba(255, 0, 0, 0.5);
padding: 10px;
border: none;
cursor: pointer;
z-index: 10;
}

/* Slide transition styles */
#slide1:checked ~ .slides {
transform: translateX(0);
}

#slide2:checked ~ .slides {
transform: translateX(-100%);
}

#slide3:checked ~ .slides {
 transform: translateX(-200%);
 }

/* Pause the slideshow (disable animation) */
#pause:checked ~ .slides {
transition: none; /* No sliding effect when paused */
}

/* Play the slideshow (enable animation) */
#play:checked ~ .slides {
transition: transform 0.5s ease; /* Enable sliding animation */
}
</style>


<div class="slideshow-container">

<input checked="" id="slide1" name="slide" type="radio">
<input id="slide2" name="slide" type="radio">
<input id="slide3" name="slide" type="radio">
    

<input id="pause" type="radio">
<input checked="" id="play" type="radio">
    

<div class="slides">
<div class="slide"><img alt="Image 1" src="image1.jpg"></div>
<div class="slide"><img alt="Image 2" src="image2.jpg"></div>
<div class="slide"><img alt="Image 3" src="image3.jpg"></div>
</div>


<label class="arrow arrow-left" for="slide1">❮</label>
<label class="arrow arrow-right" for="slide2">❯</label>
<label class="arrow arrow-right" for="slide3">❯</label>


<label class="play-pause-button" for="pause">⏸</label>
<label class="play-pause-button" for="play">▶</label>
</div>


<div class="slide"><img alt="Image 1" src="/images/School_Information.png"></div>
<div class="slide"><img alt="Image 2" src="/images/Primary_2_resize_.png"></div>
<div class="slide"><img alt="Image 3" src="/images/School_Ethos_.jpg"></div>