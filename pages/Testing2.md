---
title: Testing2
permalink: /testing2/
variant: markdown
description: ""
---
<style type="text/css">

body {

height: 100vh;
margin: 0;
background-color: #f7f7f7;
}

.card-grid {
display: grid;
grid-template-columns: repeat(2, 1fr);
gap: 40px;
width: 80%;y
height:20%;
max-width: 1200px;
max-height:500px;
}

.card {
position: relative;
width: 100%;
padding-bottom: 100%; /* Maintains square aspect ratio */
background-color: #F8F8F8;
box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
overflow: hidden;
border-radius: 10px;
cursor: pointer;
transition: transform 0.3s ease;
}

.card:hover {
transform: scale(1.05);
background-color: #ffffff;
}

.card img {
position: absolute;
top: 50%;
left: 50%;
width: 60%; /* Makes the image smaller */
height: auto;
object-fit: contain;
transform: translate(-50%, -50%); /* Centers the image */
transition: opacity 0.3s ease;
}

.card .image-hover {
opacity: 0;
}

.card:hover .image-hover {
opacity: 1;
}

.card .card-title {
font-size: 1.5em;
color: #fff;
background-color: #D3D3D3;
padding: 10px;
text-align: center;
border-radius: 5px 5px 0 0; /* Round top corners */
transition: opacity 0.3s ease;
z-index: 1; /* Ensures title stays on top of the image */
}

.card:hover .card-title {
opacity: 1;
}
</style>


<div class="card-grid">
<div class="card">
<img class="image1" alt="Image 1" src="/images/community_outreach_3.jpg">
<img class="image-hover" alt="Image 2" src="/images/Yishun_pond_2024.jpg">
<div class="card-title">Card Title 1</div>
</div>
<div class="card">
<img class="image1" alt="Image 3" src="image3.jpg">
<img class="image-hover" alt="Image 4" src="image4.jpg">
 <div class="card-title">Card Title 2</div>
 </div>
 <div class="card">
 <img class="image1" alt="Image 5" src="image5.jpg">
 <img class="image-hover" alt="Image 6" src="image6.jpg">
 <div class="card-title">Card Title 3</div>
 </div>
 </div>