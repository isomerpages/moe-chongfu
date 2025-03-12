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
  max-width: 700px;
  margin: auto;
  overflow: hidden;
  position: relative;
}

.slides {
  display: flex;
  transition: transform 0.5s ease; /* Smooth transition for sliding */
  width: 1000%; /* Adjust this to match the number of slides */
}

.slide {
  width: 10%; /* Each slide takes up 10% of the container (for 10 slides) */
  height: auto;
}

.slide img {
  width: 100%;
  height: auto;
  object-fit: cover;
  cursor: pointer; /* Make the images clickable */
}

/* Control the slide transition when the radio buttons are selected */
#slide1:checked ~ .slides {
  transform: translateX(0);
}

#slide2:checked ~ .slides {
  transform: translateX(-10%); /* Move to the second slide */
}

#slide3:checked ~ .slides {
  transform: translateX(-20%); /* Move to the third slide */
}

#slide4:checked ~ .slides {
  transform: translateX(-30%); /* Move to the fourth slide */
}

#slide5:checked ~ .slides {
  transform: translateX(-40%); /* Move to the fifth slide */
}

#slide6:checked ~ .slides {
  transform: translateX(-50%); /* Move to the sixth slide */
}

#slide7:checked ~ .slides {
transform: translateX(-60%); /* Move to the seventh slide */
}

#slide8:checked ~ .slides {
  transform: translateX(-70%); /* Move to the eighth slide */
}

#slide9:checked ~ .slides {
  transform: translateX(-80%); /* Move to the ninth slide */
}

#slide10:checked ~ .slides {
  transform: translateX(-90%); /* Move to the tenth slide */
}

/* Mobile Devices (up to 600px) */
@media (max-width: 600px) {
  .slide img {
    width: 100%;
    height: auto;
  }
}

/* Tablet devices (600px to 768px) */
@media (max-width: 768px) {
  .slide img {
    width: 100%;
    height: auto;
  }
}

/* Desktop devices (769px and above) */
@media (min-width: 769px) {
.slide img {
width: 80%;
height: auto;
}
}
</style>

<p style="text-align:justify">Our Track &amp; Field CCA aims to equip students with essential skills in running, jumping, and throwing, while promoting overall physical development. Through structured training, students gain proficiency in these fundamental athletic techniques, building confidence in their abilities.</p>
<p style="text-align:justify">In addition to regular training, select students are given the chance to participate in inter-school competitions, expanding their experiences and fostering a mindset focused on excellence and achievement. Track &amp; Field demands both mental and physical fitness, teaching students to challenge their limits and cultivate resilience.</p>
<p style="text-align:justify">Through intensive training and competition, students develop the values of sportsmanship, teamwork, and perseverance. These values not only shape their approach to track and field but also influence their overall mindset in life. Our goal is to instill a growth mindset, equipping students with skills that will inspire them to maintain a healthy lifestyle long after they graduate from Chongfu.</p>

<div class="slideshow-container">

<input checked="" id="slide1" name="slide" type="radio">
<input id="slide2" name="slide" type="radio">
<input id="slide3" name="slide" type="radio">
<input id="slide4" name="slide" type="radio">
<input id="slide5" name="slide" type="radio">
<input id="slide6" name="slide" type="radio">
<input id="slide7" name="slide" type="radio">
<input id="slide8" name="slide" type="radio">
<input id="slide9" name="slide" type="radio">
<input id="slide10" name="slide" type="radio">

<div class="slides">

<label class="slide" for="slide1">
<img alt="Image 1" src="/images/CCA%20Track%20&amp;%20Field/T_F01v.png">
</label>
<label class="slide" for="slide2">
<img alt="Image 2" src="/images/CCA%20Track%20&amp;%20Field/T_F02v.png">
</label>
<label class="slide" for="slide3">
<img alt="Image 3" src="/images/CCA%20Track%20&amp;%20Field/T_F03v.png">
</label>
<label class="slide" for="slide4">
<img alt="Image 4" src="/images/CCA%20Track%20&amp;%20Field/T_F04v.png">
</label>
<label class="slide" for="slide5">
<img alt="Image 5" src="/images/CCA%20Track%20&amp;%20Field/T_F05v.png">
</label>
<label class="slide" for="slide6">
<img alt="Image 6" src="/images/CCA%20Track%20&amp;%20Field/T_F06v.png">
</label>
<label class="slide" for="slide7">
<img alt="Image 7" src="/images/CCA%20Track%20&amp;%20Field/T_F07v.png">
</label>
<label class="slide" for="slide8">
<img alt="Image 8" src="/images/CCA%20Track%20&amp;%20Field/T_F08v.png">
</label>
<label class="slide" for="slide9">
<img alt="Image 9" src="/images/CCA%20Track%20&amp;%20Field/T_F09v.png">
</label>
<label class="slide" for="slide10">
<img alt="Image 10" src="/images/CCA%20Track%20&amp;%20Field/T_F10v.png">
</label>
</div>
</div>
