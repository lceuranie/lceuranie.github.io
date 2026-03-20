---
title: "@lceuranie"
order: 1
icon: fa-home
---

<style>
  /* 1. Hides the default section title */
  #welcome > .container > header, 
  #top > .container > header,
  #lceuranie > .container > header,
  section:first-of-type > .container > header {
    display: none !important;
  }

  /* 2. Removes the large white padding at the top of the section */
  #welcome, #top, #lceuranie, section:first-of-type {
    padding-top: 0 !important;
  }
  #welcome > .container, #top > .container, #lceuranie > .container {
    padding-top: 2em !important; /* Adjust this to 0 if you want it even higher */
  }

  /* 3. Styles the Antarctica Hero Banner */
  .hero-banner {
    background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('/assets/images/hero-bg.jpg');
    background-size: cover;
    background-position: center;
    border-radius: 12px;
    padding: 5em 2em;
    color: #ffffff;
    text-align: center;
    box-shadow: 0 10px 15px rgba(0,0,0,0.1);
    /* No more negative margin! */
    margin-top: 0; 
  }
  
  /* 4. Formatting for text and links inside the banner */
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
