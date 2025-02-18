---
title: Testing
permalink: /testing/
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
gap: 25px;
width: 80%;
max-width: 1200px;
}

.card {
display: flex;
flex-direction: column; /* Stacks the title and image vertically */
justify-content: flex-start;
width: 100%;
height: 300px; /* Set the height for the card */
background-color: #fff;
box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
overflow: hidden;
border-radius: 10px;
cursor: pointer;
transition: transform 0.3s ease;
}

.card:hover {
transform: scale(1.05);
background-color:#F8F8F8;	
}

.card .card-title {
font-size: 1.5em;
color: #fff;
background-color: rgba(0, 0, 0, 0.5);
padding: 10px;
text-align: center;
border-radius: 5px 5px 0 0; /* Round top corners */
transition: opacity 0.3s ease;
z-index: 1; /* Ensures title stays on top of the image */
}

.card .card-title {
opacity: 1;
}

.card img {
width: 80%; /* Makes the image smaller */
height: auto;
object-fit: contain;
align-self: center; /* Centers the image horizontally */
margin-top: 10px;
transition: opacity 0.3s ease;
}

.card .image-hover {
opacity: 0;
}

.card:hover .image-hover {
opacity: 1;
}
        
</style>



<div class="card-grid">
<div class="card">
<div class="card-title">Card Title 1</div>
<img class="image1" alt="Image 1" src="image1.jpg">
<img class="image-hover" alt="Image 2" src="image2.jpg">
</div>
<div class="card">
<div class="card-title">Card Title 2</div>
<img class="image1" alt="Image 3" src="image3.jpg">
<img class="image-hover" alt="Image 4" src="image4.jpg">
</div>
<div class="card">
<div class="card-title">Card Title 3</div>
<img class="image1" alt="Image 5" src="image5.jpg">
<img class="image-hover" alt="Image 6" src="image6.jpg">
</div>
</div>