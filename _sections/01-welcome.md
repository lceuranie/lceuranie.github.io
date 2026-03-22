---
title: "@lceuranie"
order: 1
icon: fa-home
---

<style>
  /* 1. Global Page/Sidebar Clean-up */
  #main, #wrapper { padding-top: 0 !important; margin-top: 0 !important; }
  #welcome > .container > header, #top > .container > header { display: none !important; }
  #nav ul li a[href="#welcome"], #nav ul li a[href="#top"] { display: none !important; }

  /* 2. HIDE THE SIDEBAR THUMBNAIL COMPLETELY */
  #header .image.avatar {
    display: none !important;
  }

  /* 3. Hero Banner Layout */
  .hero-banner {
    background: linear-gradient(rgba(0, 0, 0, 0.65), rgba(0, 0, 0, 0.65)), url('/assets/images/hero-bg.jpg');
    background-size: cover;
    background-position: center;
    padding: 6em 5%;
    color: #ffffff;
    display: flex;
    flex-wrap: wrap; /* Allows stacking on mobile */
    align-items: center;
    justify-content: center;
    gap: 4em;
    text-align: left; /* Text aligns left on desktop */
  }

  .hero-text {
    flex: 1;
    min-width: 300px;
    max-width: 650px;
  }

  .hero-image-container {
    flex: 0 1 350px;
    text-align: center;
  }

  /* 4. The Profile Image Styling */
  .profile-img {
    width: 280px;
    height: 280px;
    object-fit: cover;
    border-radius: 50%; /* Round frame like Anuj's example */
    border: 6px solid rgba(255, 255, 255, 0.2); /* Subtle glass border */
    box-shadow: 0 20px 40px rgba(0,0,0,0.3);
  }

  .hero-banner h2, .hero-banner h3, .hero-banner p {
    color: #ffffff !important; 
    border-bottom: none !important;
  }

  /* 5. Button & Spacing */
  .cv-button {
    display: inline-block;
    margin-top: 1.5em;
    padding: 0.8em 2em;
    border: 2px solid #ffffff;
    border-radius: 50px;
    color: #ffffff !important;
    text-decoration: none !important;
    font-weight: bold;
    transition: all 0.3s;
  }
  .cv-button:hover { background: #ffffff; color: #333 !important; }

  /* Mobile adjustment */
  @media screen and (max-width: 980px) {
    .hero-banner { text-align: center; padding: 4em 2em; }
    .hero-image-container { order: -1; } /* Image moves to top on mobile */
    .profile-img { width: 200px; height: 200px; }
  }
</style>

<div class="hero-banner" data-aos="fade-in" data-aos-duration="1200">

  <div class="hero-text" markdown="1">
## L. Chris Euranie
### Project Manager | Space Systems Engineer | EO Specialist

Welcome to my portfolio! I specialize in bridging earth observation & geosciences, system engineering, orbital mission design, and complex project management. 

Let’s explore my work!

<a href="/assets/L_Chris_Euranie_CV.pdf" target="_blank" class="cv-button">
  <i class="fa fa-download"></i> Download CV
</a>
  </div>

  <div class="hero-image-container">
    <img src="/assets/images/profile-headshot.jpg" alt="L. Chris Euranie" class="profile-img">
  </div>

</div>
