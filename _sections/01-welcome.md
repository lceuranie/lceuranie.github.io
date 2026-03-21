---
title: "@lceuranie"
order: 1
icon: fa-home
---

<style>
  /* 1. The "Zero Gap" fix for a perfect flush top */
  #main, #wrapper {
    padding-top: 0 !important;
    margin-top: 0 !important;
  }

  /* 2. Hides the theme's default section headers */
  #welcome > .container > header, 
  #top > .container > header,
  #lceuranie > .container > header,
  section:first-of-type > .container > header {
    display: none !important;
  }

  /* 3. Hides the redundant sidebar link */
  #nav ul li a[href="#welcome"], 
  #nav ul li a[href="#top"], 
  #nav ul li a[href="#lceuranie"] {
    display: none !important;
  }

  /* 4. Forces the container to fill 100% width with zero side-gaps */
  #welcome, #top, #lceuranie, section:first-of-type {
    padding: 0 !important;
  }

  #welcome > .container, #top > .container, #lceuranie > .container {
    max-width: 100% !important;
    width: 100% !important;
    padding: 0 !important;
    margin: 0 !important;
  }

  /* 5. Styles the Antarctica Hero Banner (Edge-to-Edge) */
  .hero-banner {
    background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('/assets/images/hero-bg.jpg');
    background-size: cover;
    background-position: center;
    border-radius: 0; /* Squared edges for full-screen feel */
    padding: 8em 2em; 
    color: #ffffff;
    text-align: center;
    width: 100%;
    margin: 0;
  }
  
  .hero-banner h2, .hero-banner h3, .hero-banner p {
    color: #ffffff !important; 
    border-bottom: none !important;
  }

  /* 6. The "Download CV" Button */
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

<div class="hero-banner" data-aos="fade-in" data-aos-duration="1200" markdown="1">

## L. Chris Euranie
### Project Manager | Space Systems Engineer | EO Specialist

<br>

Welcome to my portfolio, I specialize in bridging earth observation & geosciences, system engineering, orbital mission design, and complex project management. 

<br>

Let’s explore my work!

<br>

<a href="/assets/L_Chris_Euranie_CV.pdf" target="_blank" class="cv-button">
  <i class="fa fa-download"></i> Download CV
</a>

</div>
