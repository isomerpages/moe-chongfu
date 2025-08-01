---
title: Learn More
permalink: /our-family/
variant: markdown
description: ""
---
<style type="text/css">
  
	body {
  margin: 0;
	padding:0;
  background-color: #f4f4f4;
  }

  .card-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); /* Responsive grid */
    gap: 20px; /* Adjust gap between cards */
    width: 80%;
    max-width: 1200px;
    margin: 0 auto; /* Center the grid */
  }

	/* Overall card styles */
.card {
  position: relative;
  width: 100%;
  padding-bottom: 75%; /* Aspect ratio for rectangular shape (adjust as needed) */
  background-color: #F8F8F8;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  overflow: hidden;
  border-radius: 10px;
  cursor: pointer;
  transition: transform 0.3s ease;
}

/* Styling for images */
.card img {
  position: absolute;
  top: 63%;
  left: 50%;
  width: 100%; /* This ensures the image covers the full card */
  height: 90%; 
  object-fit: contain; /* Ensures the image fills the card without distortion */
  transform: translate(-50%, -50%); /* Centers the image */
  transition: opacity 0.5s ease-in-out; /* Smooth transition for opacity */
}

  .card:hover {
    transform: scale(1.05);
  }

  /* Title positioning */
  .card .card-title {
    font-size: 1.2em;
	  font-weight: bold;
    color: #708090;
    background-color: #F8F8F8;
    padding: 14px;
    text-align: center;
    border-radius: 5px 5px 0 0; /* Rounded top corners */
    position: absolute;
    top: 0;
    width: 100%;
    z-index: 1; /* Ensures title stays above the image */
  }

	  /* Title positioning */
  .card .card-title1 {
    font-size: 1.06em;
	  font-weight: bold;
    color: #708090;
    background-color: #F8F8F8;
    padding: 14px;
    text-align: center;
    border-radius: 5px 5px 0 0; /* Rounded top corners */
    position: absolute;
    top: 0;
    width: 100%;
    z-index: 1; /* Ensures title stays above the image */
  }
	.card:hover .card-title{
	 color: #ffffff;
	font-weight: bold;
	background-color: #d0021b;
	transition: opacity 3.0s ease-in-out; /* Smooth transition for opacity */
	}
	
	.card:hover .card-title1{
	 color: #ffffff;
	font-weight: bold;
	background-color: #d0021b;
	transition: opacity 3.0s ease-in-out; /* Smooth transition for opacity */
	}

  /* Default: image opacity set to 1 */
  .card .image1 {
    opacity: 1; /* Fully opaque initially */
  }

  /* On hover, change opacity of the image */
  .card:hover .image1 {
    opacity: 0.5; /* Make the image semi-transparent on hover */
  }

  .card .image-hover {
    opacity: 0; /* Hide the second image initially */
  }

  /* On hover, fade image 1 out and fade image 2 in */
  .card:hover .image-hover {
    opacity: 1; /* Show the second image */
  }

  .card:hover .image1 {
    opacity: 0; /* Hide the first image */
  }
	
	/* Responsive for smaller screens */
@media (max-width: 1024px) {
    .card-container {
        grid-template-columns: repeat(3, 1fr); /* 3 columns for medium screens */
    }
}

@media (max-width: 768px) {
    .card-container {
        grid-template-columns: repeat(2, 1fr); /* 2 columns for smaller screens */
    }
}

@media (max-width: 480px) {
    .card-container {
        grid-template-columns: 1fr; /* 1 column for mobile screens */
    }
}
	
</style>

<div class="card-grid">
  <div class="card">
		<div class="card-title1">School Management Committee</div>
    <img class="image1" alt="Image 1" src="/images/SMC_resize__Cool_Light.png">
		<a href="/our-family/school-management-committee/">
    <img class="image-hover" alt="Image 2" src="/images/SMC_resize_.png"></a>
  </div>
  <div class="card">
    <div class="card-title">School Steering Committee</div>
    <img class="image1" alt="Image 3" src="/images/Steering_Committee_Cool_Light.jpg">
    <a href="/our-family/school-steering-committee/">
			<img class="image-hover" alt="Image 4" src="/images/Steering_Committee.jpg"></a>
  </div>
  <div class="card">
    <div class="card-title">Non Teaching Staff</div>
    <img class="image1" alt="Image 5" src="/images/EAS_Staff_Cool_Light.jpg">
    <a href="/our-family/non-teaching-staff/">
			<img class="image-hover" alt="Image 6" src="/images/EAS_Staff.jpg"></a>
  </div>
	 <div class="card">
		 <div class="card-title">Primary 1 Teachers</div>
		 <img class="image1" alt="Image 7" src="/images/Primary_1_resize_.png">
		 <a href="/primary-1/">
			 <img class="image-hover" alt="Image 8" src="/images/Primary_1_resize_.png"></a>
  </div>
<div class="card">
		 <div class="card-title">Primary 2 Teachers</div>
		 <img class="image1" alt="Image 9" src="/images/Primary_2_resize__Vivid_Cool.png">
		 <a href="/primary-2/">
			 <img class="image-hover" alt="Image 10" src="/images/Primary_2_resize_.png"></a>
  </div>
<div class="card">
		 <div class="card-title">Primary 3 Teachers</div>
		 <img class="image1" alt="Image 11" src="/images/Primary_3_resize__Vivid_Cool.png">
		 <a href="/primary-3/">
			 <img class="image-hover" alt="Image 12" src="/images/Primary_3_resize_.png"></a>
  </div>
	<div class="card">
		 <div class="card-title">Primary 4 Teachers</div>
		 <img class="image1" alt="Image 13" src="/images/Primary_4_resize__Vivid_Cool.png">
		 <a href="/primary-4/">
			 <img class="image-hover" alt="Image 14" src="/images/Primary_4_resize_.png"></a>
  </div>
	<div class="card">
		 <div class="card-title">Primary 5 Teachers</div>
		 <img class="image1" alt="Image 15" src="/images/Primary_5_resize__Vivid_Cool.png">
		 <a href="/primary-5/">
			 <img class="image-hover" alt="Image 16" src="/images/Primary_5_resize_.png"></a>
  </div>
<div class="card">
		 <div class="card-title">Primary 6 Teachers</div>
		 <img class="image1" alt="Image 17" src="/images/Primary_6_resize__Vivid_Cool.png">
		 <a href="/primary-6/">
			 <img class="image-hover" alt="Image 18" src="/images/Primary_6_resize_.png"></a>
  </div>
</div>

<p style="font-size:16px"><strong>Updated on 28 July 2025</strong></p>