---
title: "@lceuranie"
order: 1
icon: fa-home
---

<style>
  /* === 1. Structural Fixes (Keep These) === */
  #main, #wrapper { padding-top: 0 !important; margin-top: 0 !important; }
  #welcome > .container > header, #top > .container > header, #lceuranie > .container > header, section:first-of-type > .container > header { display: none !important; }
  #nav ul li a[href="#welcome"], #nav ul li a[href="#top"], #nav ul li a[href="#lceuranie"] { display: none !important; }
  #welcome, #top, #lceuranie, section:first-of-type { padding: 0 !important; }
  #welcome > .container, #top > .container, #lceuranie > .container { max-width: 100% !important; width: 100% !important; padding: 0 !important; margin: 0 !important; }

  /* === 2. The Full-Screen Hero Container === */
  .split-hero {
    background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)), url('/assets/images/hero-bg.jpg');
    background-size: cover;
    background-position: center;
    width: 100%;
    min-height: 80vh; /* Ensures the banner has significant depth on large screens */
    color: #ffffff;
    padding: 6em 4em; /* Breathe room on sides on desktop */
    margin: 0;
    box-sizing: border-box;
  }

  /* === 3. The Flexbox Split Grid === */
  .hero-flex-container {
    display: flex;
    flex-direction: row; /* Side-by-side on desktop */
    align-items: center;  /* Vertically centers both columns */
    justify-content: center;
    gap: 4em;             /* Space between text and photo */
    max-width: 1300px;    /* Prevents content from getting too wide on massive screens */
    margin: 0 auto;       /* Centers the content block */
    flex-wrap: wrap-reverse; /* Stack photo on TOP of text on mobile */
  }

  /* === 4. Text Column (Left Side) === */
  .hero-text-column {
    flex: 1.2;             /* Text column gets slightly more space */
    text-align: left;     /* Aligns with your reference images */
    min-width: 320px;
  }

  .hero-text-column h2 {
    font-size: 3em;       /* Bold, prominent name */
    color: #ffffff !important;
    margin-bottom: 0.2em;
    border-bottom: none !important;
  }

  .hero-text-column h3 {
    font-size: 1.3em;
    color: rgba(255, 255, 255, 0.9) !important;
    margin-bottom: 1.5em;
    text-transform: uppercase;
    letter-spacing: 2px;
    font-weight: bold;
    border-bottom: none !important;
  }

  .hero-text-column p {
    font-size: 1.1em;
    line-height: 1.6;
    color: #ffffff !important;
    margin-bottom: 1em;
  }

  /* === 5. The "Download CV" Ghost Button === */
  .hero-cv-button {
    display: inline-block;
    margin-top: 2.5em;
    padding: 14px 35px;
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

  .hero-cv-button:hover {
    background: #ffffff;
    color: #333333 !important;
    transform: translateY(-3px); /* Subtler hover animation */
  }

  /* === 6. Photo Column (Right Side) === */
  .hero-photo-column {
    flex: 1;              /* Photo gets slightly less space than text */
    text-align: center;
    min-width: 350px;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  /* Your new professional photo styling */
  .pro-photo-card {
    width: 350px;         /* Specific size to feel modern and 'contained' */
    height: 350px;
    border-radius: 20px;  /* A 'squircle' or modern rounded corner box, not a circle */
    object-fit: cover;    /* Ensures your headshot doesn't stretch */
    border: 5px solid rgba(255, 255, 255, 0.2); /* Clean, modern border */
    box-shadow: 0 15px 40px rgba(0,0,0,0.5);   /* Heavy shadow for premium depth */
    transition: transform 0.4s ease;
  }

  .pro-photo-card:hover {
    transform: scale(1.03); /* Subtle pop on hover */
  }
</style>

<div class="split-hero" data-aos="fade-in" data-aos-duration="1200" markdown="1">
  
  <div class="hero-flex-container">

    <div class="hero-text-column" data-aos="fade-right" data-aos-delay="200">
      
## L. Chris Euranie
### Project Manager | Space Systems Engineer | EO Specialist

Welcome to my portfolio. I specialize in bridging earth observation & geosciences, system engineering, orbital mission design, and complex project management. 

Let’s explore my work!

<a href="/assets/L_Chris_Euranie_CV.pdf" target="_blank" class="hero-cv-button">
  <i class="fa fa-download"></i> Download CV
</a>

    </div>

    <div class="hero-photo-column" data-aos="fade-left" data-aos-delay="400">
      <img src="/assets/images/headshot.jpg" alt="L. Chris Euranie" class="pro-photo-card">
    </div>

  </div>

</div>
