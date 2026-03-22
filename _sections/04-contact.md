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

  /* The clean, borderless container */
  .contact-item {
    display: block;
    text-align: center;
    text-decoration: none !important;
    border-bottom: none !important;
    padding: 1em;
    transition: transform 0.3s ease;
  }

  /* Entire block floats gently on hover */
  .contact-item:hover {
    transform: translateY(-5px); 
  }

  /* ---------------------------------------------------- */
  /* STATE 1: Default (Grey) - Shared Across Icons & PNG */
  /* ---------------------------------------------------- */

  /* Font icon: set to correct grey (#a0a0a0) and semi-transparent */
  .contact-item .icon {
    font-size: 4em; 
    color: #a0a0a0 !important; 
    opacity: 0.6;
    transition: all 0.4s ease;
    margin-bottom: 0.2em;
    display: block;
  }

  /* PNG Image: USES A COMPLEX FILTER to precisely match the grey and opacity above */
  .contact-item .custom-img-icon {
    height: 4em; 
    width: auto;
    /* This filter sequence flattens the PNG's natural color and matches the #a0a0a0 grey */
    filter: brightness(0) saturate(100%) invert(71%) sepia(5%) saturate(0%) hue-rotate(224deg) brightness(87%) contrast(82%);
    opacity: 0.6; /* Perfect match for the native icon transparency */
    transition: all 0.4s ease;
    margin-bottom: 0.2em;
    display: inline-block;
  }

  /* -------------------------------------------------- */
  /* STATE 2: Hover (Blue) - Shared Across Icons & PNG */
  /* -------------------------------------------------- */

  /* Font icon: turns full opacity Aerospace Blue (#5a67d8) */
  .contact-item:hover .icon {
    color: #5a67d8 !important; 
    opacity: 1;
  }

  /* PNG Image: USES A COMPLEX FILTER to precisely target the #5a67d8 blue and full opacity */
  .contact-item:hover .custom-img-icon {
    /* This complex filter eradicates the natural color and injects our exact Aerospace Blue (#5a67d8) */
    filter: brightness(0) saturate(100%) invert(43%) sepia(87%) saturate(2222%) hue-rotate(213deg) brightness(91%) contrast(87%);
    opacity: 1; /* Perfect match for the native icon full opacity */
  }

  /* Label styling perfectly matched to Engagements text */
  .contact-item h4 {
    margin-top: 1.2em;
    font-size: 0.9em;
    font-weight: bold;
    color: #555;
    text-transform: uppercase;
    letter-spacing: 1px;
    border-bottom: none !important;
  }
</style>

<div data-aos="fade-up" data-aos-duration="1000">

  <p class="contact-intro">
    Feel free to reach out to discuss System Engineering, Earth Observation, Geoscience, or Project management opportunities!
  </p>

  <div class="row" style="text-align: center; margin-top: 2em;">
    
  <div class="4u 12u$(mobile)">
    <a href="mailto:lceuranie@outlook.com" class="contact-item">
      <span class="icon solid fa-envelope"></span>
      <h4>Mail</h4>
    </a>
  </div>

  <div class="4u 12u$(mobile)">
    <a href="https://www.linkedin.com/in/lceuranie" target="_blank" class="contact-item">
      <img src="assets/images/logo-linkedin.png" alt="LinkedIn" class="custom-img-icon" />
      <h4>LinkedIn</h4>
    </a>
  </div>

  <div class="4u 12u$(mobile)">
    <a href="https://www.researchgate.net/profile/Ludivine-Euranie?ev=hdr_xprf" target="_blank" class="contact-item">
      <span class="icon solid fa-graduation-cap"></span>
      <h4>ResearchGate</h4>
    </a>
  </div>

  </div>

</div>
