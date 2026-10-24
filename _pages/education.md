---
layout: page
permalink: /education/
title: education
description:
nav: true
nav_order: 1
---

<style>
  .edu-list {
    margin-top: 1rem;
  }
  .edu-item {
    display: flex;
    gap: 1.5rem;
    align-items: flex-start;
    padding: 1.75rem 0;
    border-bottom: 1px solid var(--global-divider-color);
  }
  .edu-item:last-child {
    border-bottom: none;
  }
  .edu-logo {
    flex: 0 0 76px;
    width: 76px;
    height: 76px;
    padding: 8px;
    border-radius: 14px;
    background: #fff; /* keeps logos legible in dark mode */
    border: 1px solid var(--global-divider-color);
    object-fit: contain;
  }
  .edu-body {
    flex: 1;
    min-width: 0;
  }
  .edu-body h3 {
    margin: 0 0 0.35rem;
    font-size: 1.3rem;
    font-weight: 500;
  }
  .edu-school {
    font-weight: 600;
  }
  .edu-date {
    color: var(--global-text-color-light);
    font-size: 0.95rem;
  }
  .edu-body ul {
    margin: 0.8rem 0 0;
    padding-left: 1.1rem;
  }
  .edu-body li {
    margin-bottom: 0.4rem;
    line-height: 1.6;
  }
  .edu-award {
    margin-top: 1rem;
    padding: 0.9rem 1.1rem;
    border-left: 3px solid var(--global-theme-color);
    border-radius: 6px;
    background: var(--global-card-bg-color);
  }
  .edu-cert {
    max-width: 240px;
    margin-top: 1rem;
  }
  @media (max-width: 576px) {
    .edu-item {
      gap: 1rem;
    }
    .edu-logo {
      flex-basis: 56px;
      width: 56px;
      height: 56px;
      padding: 6px;
    }
    .edu-body h3 {
      font-size: 1.15rem;
    }
  }
</style>

<div class="edu-list">

  <div class="edu-item">
    <img class="edu-logo" src="{{ '/assets/img/education/ucl.svg' | relative_url }}" alt="UCL logo">
    <div class="edu-body">
      <h3>Ph.D., Deep Learning for Point Clouds</h3>
      <div><span class="edu-school">University College London (UCL)</span></div>
      <div class="edu-date">Sep 2023 – Sep 2027 (expected)</div>
      <ul>
        <li>Funded by an EPSRC Industrial CASE studentship with <a href="https://www.ordnancesurvey.co.uk/">Ordnance Survey</a> and the UCL ISAD tuition fee support award</li>
        <li>Supervisors: <a href="https://profiles.ucl.ac.uk/27481-jan-boehm">Prof. Jan Boehm</a> (UCL), Prof. Stuart Robson (UCL), Dr. Stefano Cavazzi (Ordnance Survey), James Gillespie (Ordnance Survey)</li>
        <li>Member of the <a href="https://www.ucl.ac.uk/civil-environmental-geomatic-engineering/research/groups-centres-and-sections/photogrammetry-and-3d-imaging">Photogrammetry and 3D Imaging</a> research group</li>
      </ul>
    </div>
  </div>

  <div class="edu-item">
    <img class="edu-logo" src="{{ '/assets/img/education/polyu.svg' | relative_url }}" alt="PolyU logo">
    <div class="edu-body">
      <h3>Visiting Ph.D. Student, Deep Learning for Point Clouds</h3>
      <div><span class="edu-school">The Hong Kong Polytechnic University (PolyU)</span></div>
      <div class="edu-date">Sep 2026 – Jan 2027</div>
      <ul>
        <li><a href="https://www.polyu.edu.hk/gs/prospective-students/rsap_incoming/">Research Student Attachment Programme (RSAP)</a></li>
        <li>Host supervisor: <a href="https://bingcs.github.io/">Prof. Bing Wang</a></li>
      </ul>
    </div>
  </div>

  <div class="edu-item">
    <img class="edu-logo" src="{{ '/assets/img/education/ucl.svg' | relative_url }}" alt="UCL logo">
    <div class="edu-body">
      <h3>M.Sc., Machine Learning</h3>
      <div><span class="edu-school">University College London (UCL)</span></div>
      <div class="edu-date">2021 – 2023</div>
      <ul>
        <li>Dissertation carried out in collaboration with the <a href="https://deepcamera.cyens.org.cy/">DeepCamera Group, CYENS</a> (Cyprus) and published in <em>Automation in Construction</em>: <a href="https://doi.org/10.1016/j.autcon.2024.105960">Hybrid-Segmentor: Hybrid Approach for Automated Fine-Grained Crack Segmentation in Civil Infrastructure</a></li>
      </ul>
    </div>
  </div>

  <div class="edu-item">
    <img class="edu-logo" src="{{ '/assets/img/education/bath.png' | relative_url }}" alt="University of Bath logo">
    <div class="edu-body">
      <h3>M.Sc., Data Science</h3>
      <div><span class="edu-school">University of Bath</span></div>
      <div class="edu-date">2019 – 2020</div>
      <ul>
        <li>Dissertation: <em>Prediction of Fine Particulate Matter Concentration in Seoul Using an Ensemble Voting Classifier</em></li>
      </ul>
    </div>
  </div>

  <div class="edu-item">
    <img class="edu-logo" src="{{ '/assets/img/education/bristol.png' | relative_url }}" alt="University of Bristol logo">
    <div class="edu-body">
      <h3>B.Eng., Engineering Mathematics</h3>
      <div><span class="edu-school">University of Bristol</span></div>
      <div class="edu-date">2015 – 2019</div>
      <ul>
        <li>Final year project: <em>Socio-Economic Deprivation Analysis: Diffusion Map</em></li>
      </ul>
      <div class="edu-award">
        🏆 <strong>BEng Engineering Mathematics Student Prize</strong><br>
        Awarded by the Department of Engineering Mathematics for the BEng Final Year Project (22 July 2019)
        <div class="edu-cert">
          {% include figure.liquid loading="lazy" path="assets/img/education/bristol_prize_2019.jpg" class="img-fluid rounded z-depth-1" zoomable=true alt="BEng Engineering Mathematics Student Prize certificate, University of Bristol, 22 July 2019" %}
        </div>
      </div>
    </div>
  </div>

</div>
