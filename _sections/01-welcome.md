---
title: "@lceuranie"
order: 1
icon: fa-home
---

<style>
  /* 1. Hides the theme's default section title */
  #welcome > .container > header, 
  #top > .container > header {
    display: none !important;
  }

  /* 2. Styles the Antarctica Hero Banner */
  .hero-banner {
    /* Linear-gradient provides a 60% dark tint for readability */
    background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('/assets/images/hero-bg.jpg');
    background-size: cover;
    background-position: center;
    border-radius: 12px;
    padding: 6em 2em; /* Slightly more padding for better vertical balance */
    color: #ffffff;
    text-align: center;
    box-shadow: 0 10px 15px rgba(0,0,0,0.1);
    margin-top: -3em; /* Pulls the banner up to fill the gap left by the hidden title */
  }
  
  /* 3. Ensures all text inside the banner is strictly white */
  .hero-banner h2, 
  .hero-banner h3, 
  .hero-banner p, 
  .hero-banner strong {
    color: #ffffff !important; 
  }
</style>

<div class="hero-banner" data-aos="fade-up" data-aos-duration="1000" markdown="1">

## L. Chris Euranie
### Project Manager | Space Systems Engineer | EO Specialist

Welcome to my portfolio! I specialize in bridging earth observation & geosciences, system engineering, orbital mission design, and complex project management. Let’s explore my work.

</div>
