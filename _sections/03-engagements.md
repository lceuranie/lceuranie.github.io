---
title: My Engagements
order: 3
icon: fa-users
---

<style>
  .engagement-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 2em;
    padding: 2em 0;
  }

  .engagement-item {
    flex: 1;
    min-width: 200px;
    max-width: 250px;
    text-align: center;
    transition: transform 0.3s ease;
  }

  .engagement-item:hover {
    transform: translateY(-5px);
  }

  .engagement-logo {
    width: 100%;
    height: 120px;
    object-fit: contain;
    filter: grayscale(100%);
    opacity: 0.6;
    transition: all 0.4s ease;
    margin-bottom: 1em;
  }

  .engagement-item:hover .engagement-logo {
    filter: grayscale(0%);
    opacity: 1;
  }

  .engagement-name {
    font-size: 0.9em;
    font-weight: bold;
    color: #555;
    text-transform: uppercase;
    letter-spacing: 1px;
  }
</style>

<div class="engagement-grid" data-aos="fade-up">

  <a href="https://www.wia-europe.org/" target="_blank" class="engagement-item">
    <img src="assets/images/logo-wia.png" alt="WIA Strasbourg" class="engagement-logo">
    <div class="engagement-name">WIA-Strasbourg</div>
  </a>

  <a href="https://www.ipgp.fr/" target="_blank" class="engagement-item">
    <img src="assets/images/logo-ipgp.png" alt="IPGP Alumni" class="engagement-logo">
    <div class="engagement-name">IPGP Alumni</div>
  </a>

  <a href="https://www.isunet.edu/" target="_blank" class="engagement-item">
    <img src="assets/images/logo-isu.png" alt="ISU Alumni" class="engagement-logo">
    <div class="engagement-name">ISU Alumni</div>
  </a>

  <div class="engagement-item">
    <span class="icon solid fa-camera" style="font-size: 4em; color: #ccc; display: block; margin-bottom: 0.2em;"></span>
    <div class="engagement-name" style="margin-top: 1.2em;">Travel Photography</div>
  </div>

</div>
