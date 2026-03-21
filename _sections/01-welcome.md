---
title: "@lceuranie"
order: 1
icon: fa-home
---

<style>
  /* 1. Hides the default section title on the page */
  #welcome > .container > header, 
  #top > .container > header,
  #lceuranie > .container > header,
  section:first-of-type > .container > header {
    display: none !important;
  }

  /* 2. Hides the redundant "@lceuranie" link from the sidebar navigation */
  #nav ul li a[href="#welcome"], 
  #nav ul li a[href="#top"], 
  #nav ul li a[href="#lceuranie"] {
    display: none !important;
  }

  /* 3. Removes large white padding at the top of the section */
  #welcome, #top, #lceuranie, section:first-of-type {
    padding-top: 0 !important;
  }
  #welcome > .container, #top > .container, #lceuranie > .container {
    padding-top: 2em !important;
  }

  /* 4. Styles the Antarctica Hero Banner */
  .hero-banner {
    background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('/assets/images/hero-bg.jpg');
    background-size: cover;
    background-position: center;
    border-radius: 12px;
    padding: 6em 2em;
    color: #ffffff;
    text-align: center;
    box-shadow: 0 10px 15px rgba(0,0,0,0.1);
    margin-top: 0; 
  }
  
  .hero-banner h2, .hero-banner h3, .hero-banner p {
    color: #ffffff !important; 
    border-bottom: none !important;
  }

  /* 5. The "Download CV" Button Style */
  .cv-button {
    display: inline-block;
    margin-top: 1.5em;
    padding: 0.75em 2em;
    background: transparent;
    color: #ffffff !important;
    border: 2px solid #ffffff;
    border-radius: 50px;
    font-weight: bold;
    text-decoration: none !important;
    transition: all 0.3s ease;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-size: 0.9em;
  }

  .cv-button:hover {
    background: #ffffff;
    color: #333333 !important;
    transform: scale(1.05);
  }
</style>

<div class="hero-banner" data-aos="fade-up" data-aos-duration="1000" markdown="1">

## L. Chris Euranie
### Project Manager | Space Systems Engineer | EO Specialist

<br>

Welcome to my portfolio, I specialize in bridging earth observation & geosciences, system engineering, orbital mission design, and complex project management. 
<br>
Let’s explore my work !
<br>

<a href="/assets/L_Chris_Euranie_CV.pdf" target="_blank" class="cv-button">
  <i class="fa fa-download"></i> Download CV
</a>

</div>
