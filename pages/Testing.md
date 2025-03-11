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
 position: relative;
 width: 100%;
 max-width: 600px;
 margin: auto;
 overflow: hidden;
 }

.slides {
display: flex;
transition: transform 0.5s ease-in-out;
}

.slide {
width: 100%; /* Each slide takes up 100% of the container */
height: auto;
}

.slide img {
width: 100%;
height: auto;
}

/* Navigation arrows */
.arrow {
position: absolute;
top: 50%;
transform: translateY(-50%);
font-size: 2em;
color: #fff;
background-color: rgba(0, 0, 0, 0.5);
padding: 10px;
border: none;
cursor: pointer;
z-index: 10;
}

.arrow-left {
left: 10px;
}

.arrow-right {t
right: 10px;
}

/* Slide transition styles */
#slide1:target ~ .slides {
transform: translateX(0);
}

#slide2:target ~ .slides {
transform: translateX(-100%);
}

#slide3:target ~ .slides {
transform: translateX(-200%);
}
</style>


<div class="slideshow-container">

<a class="arrow arrow-left" href="#slide1">❮</a>
<a class="arrow arrow-right" href="#slide2">❯</a>
<a class="arrow arrow-right" href="#slide3">❯</a>


<div class="slides">
<div class="slide"><img id="slide1" alt="Image 1" src="/images/School_Information.png"></div>
<div class="slide"><img id="slide2" alt="Image 2" src="/images/Primary_6_resize_.png"></div>
<div class="slide"><img id="slide3" alt="Image 3" src="/images/Primary_1_resize_.png"></div>
</div>
</div>
