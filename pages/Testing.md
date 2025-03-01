---
title: Testing
permalink: /testing/
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

  .card {
    position: relative;
    width: 100%;
    padding-bottom: 75%; /* Aspect ratio for rectangular shape (can change this) */
    background-color: #F8F8F8;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    overflow: hidden;
    border-radius: 10px;
    cursor: pointer;
    transition: transform 0.3s ease;
  }

  .card:hover {
    transform: scale(1.05);
  }

  /* Title positioning */
  .card .card-title {
    font-size: 1.5em;
	  font-weight: bold;
    color: #708090;
    background-color: #F8F8F8;
    padding: 10px;
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
	
  /* Styling for images */
  .card img {
    position: absolute;
    top: 50%;
    left: 50%;
    width: 100%;
    height: 100%;
    object-fit: cover; /* Ensures the image fills the card */
    transform: translate(-50%, -50%); /* Centers the image */
    transition: opacity 0.5s ease-in-out; /* Smooth transition for opacity */
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
		<div class="card-title">Our History</div>
    <img class="image1" alt="Image 1" src="/images/Our_History__Thian_Hock_Keng_Painting__Alfred_Agate_c__1842____Vivid_Cool.jpg">
		<a href="/our-school/history/">
    <img class="image-hover" alt="Image 2" src="/images/Our_History__Thian_Hock_Keng_Painting__Alfred_Agate_c__1842_.jpg"></a>
  </div>
  <div class="card">
    <div class="card-title">School Ethos</div>
    <img class="image1" alt="Image 3" src="/images/School_Ethos____Vivid_Cool.jpg">
    <a href="/our-school/school-ethos/">
			<img class="image-hover" alt="Image 4" src="/images/School_Ethos_.jpg"></a>
  </div>
  <div class="card">
    <div class="card-title">School Identity</div>
    <img class="image1" alt="Image 5" src="/images/School_Identity____Vivid_Cool.jpg">
    <a href="/our-school/school-identity/">
			<img class="image-hover" alt="Image 6" src="/images/School_Identity_.jpg"></a>
  </div>
	 <div class="card">
		 <div class="card-title">School Information</div>
		 <img class="image1" alt="Image 5" src="/images/School_Information____Vivid_Cool.jpg">
		 <a href="/school-information/">
			 <img class="image-hover" alt="Image 6" src="/images/School_Information_.jpg"></a>
  </div>
</div>