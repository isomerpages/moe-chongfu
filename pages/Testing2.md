---
title: Testing2
permalink: /testing2/
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
transition: transform 0.5s ease; /* Smooth transition for sliding */
}

.slide {
width: 100%; /* Each slide takes up 100% of the container */
height: auto;
}

.slide img {
width: 100%;
height: auto;
object-fit: cover;
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

/* Control the slide transition when the radio buttons are selected */
#slide1:checked ~ .slides {
transform: translateX(0);
}

#slide2:checked ~ .slides {
transform: translateX(-100%); /* Move the slides to the left */
}

#slide3:checked ~ .slides {
transform: translateX(-200%);
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
</style>


<div class="slideshow-container">

<input checked="" id="slide1" name="slide" type="radio">
<input id="slide2" name="slide" type="radio">
<input id="slide3" name="slide" type="radio">
    
 
 <div class="slides">
 <div class="slide"><img alt="Image 1" src="/images/School_Information.png"></div>
 <div class="slide"><img alt="Image 2" src="/images/Primary_2_resize_.png"></div>
 <div class="slide"><img alt="Image 3" src="/images/School_Ethos_.jpg"></div>
 </div>


<label class="arrow arrow-left" for="slide1">❮</label>
<label class="arrow arrow-right" for="slide2">❯</label>
<label class="arrow arrow-right" for="slide3">❯</label>
</div>

