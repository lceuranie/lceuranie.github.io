---
title: "@lceuranie"
order: 1
icon: fa-home
---

<style>
  /* 1. The "Nuclear Option" to hide that specific section header */
  /* This covers #welcome, #top, and the likely ID generated from your title: #lceuranie */
  #welcome > .container > header, 
  #top > .container > header,
  #lceuranie > .container > header,
  section:first-of-type > .container > header {
    display: none !important;
    visibility: hidden !important;
    height: 0 !important;
    margin: 0 !important;
    padding: 0 !important;
  }

  /* 2. Styles the Antarctica Hero Banner */
  .hero-banner {
    background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('/assets/images/hero-bg.jpg');
    background-size: cover;
    background-position: center;
    border-radius: 12px;
    padding: 5em 2em;
    color: #ffffff;
    text-align: center;
    box-shadow: 0 10px 15px rgba(0,0,0,0.1);
    /* Pulls the banner up to fill the gap left by the hidden title */
    margin-top: -4em; 
  }
  
  /* 3. Forces all text inside the banner to be white */
  .hero-banner h2, 
  .hero-banner h3, 
  .hero-banner p, 
  .hero-banner strong {
    color: #ffffff !important; 
    border-bottom: none !important;
  }
</style>

<div class="hero-banner" data-aos="fade-up" data-aos-duration="1000" markdown="1">

## L. Chris Euranie
### Project Manager | Space Systems Engineer | EO Specialist
  
Welcome to my portfolio! I specialize in bridging earth observation & geosciences, system engineering, orbital mission design, and complex project management. Let’s explore my work.

</div>
