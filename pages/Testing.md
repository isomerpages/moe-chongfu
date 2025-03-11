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
animation: slideAnimation 9s infinite;
}

.slide {
width: 100%; /* Each slide takes up 100% of the container */
height: auto;
}

.slide img {
width: 100%;
height: auto;
}

/* Animation to shift the slides */
@keyframes slideAnimation {
0% {
transform: translateX(0);
}
33% {
transform: translateX(-100%);
}
66% {
transform: translateX(-200%);
}
100% {
transform: translateX(0);
}
}
</style>

<div class="slideshow-container">
<div class="slides">
<div class="slide"><img alt="Image 1" src="image1.jpg"></div>
<div class="slide"><img alt="Image 2" src="image2.jpg"></div>
<div class="slide"><img alt="Image 3" src="image3.jpg"></div>
</div>
</div>

