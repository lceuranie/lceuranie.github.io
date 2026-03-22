---
title: Contact
order: 4
icon: fa-envelope
---

<style>
  .contact-intro {
    font-size: 1.1em;
    margin-bottom: 3em;
    color: #555;
    line-height: 1.6;
  }

  /* Creates the interactive white card */
  .contact-card {
    display: block;
    background: #ffffff;
    padding: 3em 1em;
    border-radius: 12px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.05);
    transition: all 0.3s ease;
    text-decoration: none !important;
    border-bottom: none !important;
    height: 100%;
  }

  /* Card floats up and shadow deepens on hover */
  .contact-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 12px 25px rgba(0,0,0,0.1);
  }

  /* Default grey state for native font icons */
  .contact-card .icon {
    font-size: 3.5em;
    color: #a0a0a0;
    transition: all 0.3s ease;
    margin-bottom: 0.3em;
    display: block;
  }

  /* Default grey state for your custom PNG image */
  .contact-card .custom-img-icon {
    height: 3.5em; /* Matches the 3.5em font-size of the regular icons */
    width: auto;
    filter: grayscale(100%);
    opacity: 0.55; /* Blends it to look like the #a0a0a0 grey */
    transition: all 0.3s ease;
    margin-bottom: 0.3em;
    display: inline-block;
  }

  /* Hover state: Font icons turn Aerospace Blue */
  .contact-card:hover .icon {
    color: #5a67d8; 
    transform: scale(1.1);
  }

  /* Hover state: PNG Image loses grayscale and scales up */
  .contact-card:hover .custom-img-icon {
    filter: grayscale(0%);
    opacity: 1;
    transform: scale(1.1);
  }

  .contact-card h4 {
    margin: 0;
    font-weight: bold;
    color: #333;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-size: 1em;
  }
</style>

<div data-aos="fade-up" data-aos-duration="1000">

  <p class="contact-intro">
    Feel free to reach out to discuss System Engineering, Earth Observation, Geoscience, or Project management opportunities!
  </p>

  <div class="row" style="text-align: center;">
    
  <div class="4u 12u$(mobile)">
    <a href="mailto:lceuranie@outlook.com" class="contact-card">
      <span class="icon solid fa-envelope"></span>
      <h4>Mail</h4>
    </a>
  </div>

  <div class="4u 12u$(mobile)">
    <a href="https://www.linkedin.com/in/lceuranie" target="_blank" class="contact-card">
      <img src="assets/images/logo-linkedin.png" alt="LinkedIn" class="custom-img-icon" />
      <h4>LinkedIn</h4>
    </a>
  </div>

  <div class="4u 12u$(mobile)">
    <a href="https://www.researchgate.net/profile/Ludivine-Euranie?ev=hdr_xprf" target="_blank" class="contact-card">
      <span class="icon solid fa-graduation-cap"></span>
      <h4>ResearchGate</h4>
    </a>
  </div>

  </div>

</div>
