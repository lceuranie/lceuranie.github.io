---
title: My Projects
order: 2
icon: fa-rocket
---

<style>
  .modern-card {
    background: #ffffff;
    border-radius: 12px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05), 0 1px 3px rgba(0,0,0,0.1);
    overflow: hidden;
    margin-bottom: 2em;
    text-align: left;
    transition: transform 0.2s ease-in-out;
    border: 1px solid #eaeaea;
    /* Flexbox rules to make heights uniform */
    display: flex;
    flex-direction: column;
    width: 100%;
  }
  .modern-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 15px rgba(0,0,0,0.1);
  }
  .card-img {
    width: 100%;
    aspect-ratio: 16/9;
    object-fit: cover;
    border-bottom: 1px solid #eaeaea;
    display: block;
  }
  .card-body {
    padding: 1.2em; /* Reduced for a more compact, less bulky look */
    display: flex;
    flex-direction: column;
    flex-grow: 1; /* Forces the body to stretch and fill the empty space */
  }
  .card-title {
    margin: 0 0 0.5em 0;
    font-size: 1.1em; /* Slightly smaller */
    font-weight: bold;
  }
  .card-title a {
    color: #5a67d8; 
    border-bottom: none;
    text-decoration: none;
  }
  .card-desc {
    font-size: 0.85em; /* Slightly smaller text */
    color: #666;
    line-height: 1.5;
    margin-bottom: 1.2em;
  }
  .card-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-top: auto; /* This magically pushes the tags to the very bottom */
  }
  .tag {
    background: #edf2f7;
    color: #4a5568;
    padding: 4px 10px;
    border-radius: 20px;
    font-size: 0.75em;
    font-weight: 600;
  }
</style>

<div class="row" style="display: flex; flex-wrap: wrap; align-items: stretch;">

  <div class="4u 12u$(mobile)" style="display: flex;">
    <div class="modern-card" data-aos="fade-up">
      <a href="project-ai.html"><img src="assets/images/thumbnail-ai-169.png" alt="AI Proficiency" class="card-img" /></a>
      <div class="card-body">
        <h3 class="card-title"><a href="project-ai.html">AI Proficiency</a></h3>
        <p class="card-desc">Showcasing AI capabilities including agent building and deployment.</p>
        <div class="card-tags">
          <span class="tag">Artificial Intelligence</span>
          <span class="tag">Agent Building</span>
        </div>
      </div>
    </div>
  </div>

  <div class="4u 12u$(mobile)" style="display: flex;">
    <div class="modern-card" data-aos="fade-up">
      <a href="project-gis.html"><img src="assets/images/thumbnail-gis2-169.jpg" alt="Geographic Information System" class="card-img" /></a>
      <div class="card-body">
        <h3 class="card-title"><a href="project-gis.html">GIS</a></h3>
        <p class="card-desc">Analyzing satellite data to provide communities with valuable vegetation health information.</p>
        <div class="card-tags">
          <span class="tag">GEE</span>
          <span class="tag">Remote Sensing</span>
          <span class="tag">EO</span>
        </div>
      </div>
    </div>
  </div>

  <div class="4u 12u$(mobile)" style="display: flex;">
    <div class="modern-card" data-aos="fade-up">
      <a href="project-geosciences.html"><img src="assets/images/thumbnail-geosciences-169.png" alt="Geosciences" class="card-img" /></a>
      <div class="card-body">
        <h3 class="card-title"><a href="project-geosciences.html">Geosciences</a></h3>
        <p class="card-desc">10 years in Oil & Gas, leading geoscientific studies for exploration, and field development.</p>
        <div class="card-tags">
          <span class="tag">Geophysics</span>
          <span class="tag">Borehole Seismic</span>
          <span class="tag">Field Operations</span>
        </div>
      </div>
    </div>
  </div>

  <div class="4u 12u$(mobile)" style="display: flex;">
    <div class="modern-card" data-aos="fade-up">
      <a href="project-systems.html"><img src="assets/images/thumbnail-systems-169.png" alt="System Engineering" class="card-img" /></a>
      <div class="card-body">
        <h3 class="card-title"><a href="project-systems.html">System Engineering</a></h3>
        <p class="card-desc">1U CubeSat system integration, Model-Based Systems Engineering (MBSE), and PCB design.</p>
        <div class="card-tags">
          <span class="tag">CubeSat</span>
          <span class="tag">MBSE</span>
          <span class="tag">Concurrent Engineering</span>
        </div>
      </div>
    </div>
  </div>

  <div class="4u 12u$(mobile)" style="display: flex;">
    <div class="modern-card" data-aos="fade-up">
      <a href="project-management.html"><img src="assets/images/thumbnail-management-169.png" alt="Project Management" class="card-img" /></a>
      <div class="card-body">
        <h3 class="card-title"><a href="project-management.html">Project Management</a></h3>
        <p class="card-desc">Managing multidisciplinary engineering teams through complex projects' life cycles.</p>
        <div class="card-tags">
          <span class="tag">Leadership</span>
          <span class="tag">Governance</span>
          <span class="tag">Risk Analytics</span>
        </div>
      </div>
    </div>
  </div>

  <div class="4u 12u$(mobile)" style="display: flex;">
    <div class="modern-card" data-aos="fade-up">
      <a href="project-orbital.html"><img src="assets/images/thumbnail-orbital-169.jpg" alt="Orbital Mission Design" class="card-img" /></a>
      <div class="card-body">
        <h3 class="card-title"><a href="project-orbital.html">Orbital Mission Design</a></h3>
        <p class="card-desc">Modeling satellites, ground stations, coverage, and orbits in a realistic 3D environment.</p>
        <div class="card-tags">
          <span class="tag">STK</span>
          <span class="tag">Mission Analysis</span>
        </div>
      </div>
    </div>
  </div>

  <div class="4u 12u$(mobile)" style="display: flex;">
    <div class="modern-card" data-aos="fade-up">
      <a href="project-astronomical.html"><img src="assets/images/thumbnail-astronomical-169.png" alt="Astronomical Data Mining" class="card-img" /></a>
      <div class="card-body">
        <h3 class="card-title"><a href="project-astronomical.html">Astronomical Data Mining</a></h3>
        <p class="card-desc">Utilizing Gaia data release 3 (GDR3) to analyze open clusters.</p>
        <div class="card-tags">
          <span class="tag">Astrophysics</span>
          <span class="tag">Gaia DR3</span>
          <span class="tag">Open Clusters</span>
        </div>
      </div>
    </div>
  </div>

  <div class="4u 12u$(mobile)" style="display: flex;">
    <div class="modern-card" data-aos="fade-up">
      <a href="project-deepspace.html"><img src="assets/images/thumbnail-deepspace-169.jpg" alt="Deep Space Communication" class="card-img" /></a>
      <div class="card-body">
        <h3 class="card-title"><a href="project-deepspace.html">Deep Space Communication</a></h3>
        <p class="card-desc">A John Templeton Grant project developing a global communication roadmap to sustain exploration missions.</p>
        <div class="card-tags">
          <span class="tag">Grant</span>
          <span class="tag">IAC Paper</span>
        </div>
      </div>
    </div>
  </div>

  <div class="4u 12u$(mobile)" style="display: flex;">
    <div class="modern-card" data-aos="fade-up">
      <a href="project-sbsp.html"><img src="assets/images/thumbnail-sbsp-169.png" alt="Space Based Solar Power Thesis" class="card-img" /></a>
      <div class="card-body">
        <h3 class="card-title"><a href="project-sbsp.html">Space Based Solar Power Thesis</a></h3>
        <p class="card-desc">A thematic synthesis of architectural evolution and policy frameworks of SBSP technology.</p>
        <div class="card-tags">
          <span class="tag">SBSP</span>
          <span class="tag">Policy Frameworks</span>
        </div>
      </div>
    </div>
  </div>

</div>
