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
grid-template-columns: repeat(3, 1fr);
gap: 20px;
width: 80%;
max-width: 1200px;
}

.card {
position: relative;
width: 100%;
padding-bottom: 100%; /* Maintains square aspect ratio */
background-color: #fff;
box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
overflow: hidden;
border-radius: 10px;
cursor: pointer;
transition: transform 0.3s ease;
}

.card:hover {
transform: scale(1.05);
}

.card img {
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
object-fit: cover;
transition: opacity 0.3s ease;
}

.card .card-title {
position: absolute;
bottom: 10px;
left: 10px;
right: 10px;
font-size: 1.2em;
color: #dd;
padding: 10px;
text-align: center;
border-radius: 5px;
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
<img style="width:20%" class="image1" alt="Image 1" src="/images/community_outreach_3.jpg">
<img class="image-hover" alt="Image 2" src="/images/Chinese_New_Year_Celebration.jpg">
<div class="card-title">title 1</div>
</div>
<div class="card">
<img class="image1" alt="Image 3" src="image3.jpg">
<img class="image-hover" alt="Image 4" src="image4.jpg">
</div>
<div class="card">
<img class="image1" alt="Image 5" src="image5.jpg">
<img class="image-hover" alt="Image 6" src="image6.jpg">
</div>
</div>