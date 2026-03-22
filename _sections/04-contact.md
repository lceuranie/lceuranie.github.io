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

  /* Font icon default state: grey and semi-transparent */
  .contact-item .icon {
    font-size: 4em; /* Matched to the Engagements icon size */
    color: #a0a0a0; 
    opacity: 0.6;
    transition: all 0.4s ease;
    margin-bottom: 0.2em;
    display: block;
  }

  /* PNG icon default state: grayscale and semi-transparent */
  .contact-item .custom-img-icon {
    height: 4em; /* Matched to the Font icon size */
    width: auto;
    filter: grayscale(100%);
    opacity: 0.6;
    transition: all 0.4s ease;
    margin-bottom: 0.2em;
    display: inline-block;
  }

  /* Font icon hover state: jumps to full opacity Aerospace Blue */
  .contact-item:hover .icon {
    color: #5a67d8; 
    opacity: 1;
  }

  /* PNG icon hover state: jumps to full opacity and natural color */
  .contact-item:hover .custom-img-icon {
    filter: grayscale(0%);
    opacity: 1;
  }

  /* Label styling perfectly matched to Engagements text */
  .contact-item h4 {
    margin-top: 1.2em;
    font-size: 0.9em;
    font-weight: bold;
    color: #555;
    text-transform: uppercase;
    letter-spacing: 1px;
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
