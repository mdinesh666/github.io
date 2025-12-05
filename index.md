---
layout: home
title: Portfolio
permalink: /
---

<style>
  /* --- GLOBAL TYPOGRAPHY ENHANCEMENTS --- */
  body {
    /* Uses the crispest system fonts available */
    font-family: -apple-system, BlinkMacSystemFont, "Inter", "Segoe UI", Roboto, sans-serif;
    -webkit-font-smoothing: antialiased; /* Makes text look sharper on Mac */
    color: #222;
  }

  /* --- GRID LAYOUT --- */
  .project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); /* Auto-responsive */
    gap: 40px; /* More breathing room between cards */
    margin-top: 4rem;
    margin-bottom: 5rem;
  }

  /* --- CARD DESIGN (THE BEAUTIFICATION) --- */
  .project-card {
    background: #ffffff;
    border: 1px solid rgba(0,0,0,0.06); /* Very subtle border */
    border-radius: 16px; /* Modern rounded corners */
    text-decoration: none !important;
    color: inherit;
    transition: all 0.4s cubic-bezier(0.25, 0.8, 0.25, 1); /* Smooth "Apple-like" animation */
    display: flex;
    flex-direction: column;
    overflow: hidden;
    position: relative;
    box-shadow: 0 4px 6px rgba(0,0,0,0.02); /* Barely visible shadow at rest */
  }

  /* Hover State: The "Lift" */
  .project-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 20px 40px rgba(0,0,0,0.08); /* Soft, diffuse shadow on hover */
    border-color: rgba(0,0,0,0.0); /* Border disappears on hover for cleaner look */
  }

  /* --- IMAGE STYLING --- */
  .card-img-container {
    height: 240px;
    overflow: hidden;
    position: relative;
    background: #f4f4f4;
  }

  .card-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.6s ease;
  }

  /* Zoom effect on image hover */
  .project-card:hover .card-img {
    transform: scale(1.03);
  }

  /* --- CONTENT & TYPOGRAPHY HIERARCHY --- */
  .card-content {
    padding: 32px 28px; /* Generous padding feels premium */
    flex-grow: 1;
    display: flex;
    flex-direction: column;
  }

  /* The "Eyebrow" Date */
  .project-date {
    font-size: 0.75rem;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 1.5px; /* Spaced out letters look expensive */
    color: #999;
    margin-bottom: 12px;
    display: block;
  }

  /* The Title */
  .project-card h3 {
    margin-top: 0;
    margin-bottom: 12px;
    font-size: 1.5rem; /* Larger title */
    font-weight: 700;
    color: #111;
    line-height: 1.2;
    letter-spacing: -0.5px; /* Tighter letter spacing for headlines */
  }

  /* The Description */
  .project-card p {
    font-size: 1.05rem;
    color: #666;
    line-height: 1.6; /* More space between lines for readability */
    margin-bottom: 0;
    font-weight: 400;
  }

  /* --- INTRO SECTION TYPOGRAPHY --- */
  .intro-text {
    font-size: 1.25rem;
    line-height: 1.7;
    color: #444;
    max-width: 700px;
    margin-bottom: 3rem;
  }
  
  .intro-name {
    font-weight: 800;
    color: #000;
  }

  /* Mobile Tweaks */
  @media (max-width: 600px) {
    .project-grid { gap: 24px; }
    .card-content { padding: 24px; }
    .project-card h3 { font-size: 1.3rem; }
  }
</style>

<div class="intro-text">
  Hi, I'm <span class="intro-name">Muthudinesh</span>.<br>
  I'm a Product Designer at Congruent. By day, I build robust enterprise applications. By night, I tinker with electronics and AI. I bridge the gap between "it looks good" and "it actually works."
</div>

<h2 style="font-weight: 800; font-size: 2rem; letter-spacing: -1px; margin-bottom: 2rem;">Selected Works</h2>

<div class="project-grid">

  <a href="./project-1" class="project-card">
    <div class="card-img-container">
       <img src="https://picsum.photos/id/1/800/600" alt="GPS Device Prototype" class="card-img">
    </div>
    <div class="card-content">
      <span class="project-date">Oct 2025</span>
      <h3>GPS Navigator</h3>
      <p>A minimalist pure navigation hardware device built for delivery partners using ESP32.</p>
    </div>
  </a>

  <a href="#" class="project-card">
    <div class="card-img-container">
       <img src="https://picsum.photos/id/2/800/600" alt="Email System" class="card-img">
    </div>
    <div class="card-content">
      <span class="project-date">Sep 2025</span>
      <h3>Email System Design</h3>
      <p>Redesigning the HTML email template structure for better responsive behavior.</p>
    </div>
  </a>

  <a href="#" class="project-card">
    <div class="card-img-container">
       <img src="https://picsum.photos/id/3/800/600" alt="AI Agent" class="card-img">
    </div>
    <div class="card-content">
      <span class="project-date">Aug 2025</span>
      <h3>Figma to Code Agent</h3>
      <p>An AI experiment leveraging prompt engineering to automate design-to-dev handoffs.</p>
    </div>
  </a>

  <a href="#" class="project-card">
    <div class="card-img-container">
       <img src="https://picsum.photos/id/4/800/600" alt="Design System" class="card-img">
    </div>
    <div class="card-content">
      <span class="project-date">Jul 2025</span>
      <h3>Enterprise Design System</h3>
      <p>Building a robust UI kit and documentation for complex 401k record-keeping dashboards.</p>
    </div>
  </a>

</div>
