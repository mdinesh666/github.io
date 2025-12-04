---
layout: home
permalink: /
---

<style>
  /* 1. The Grid Container */
  .project-grid {
    display: grid;
    grid-template-columns: 1fr 1fr; /* Creates 2 equal columns */
    gap: 20px; /* Space between cards */
    margin-top: 2rem;
  }

  /* 2. The Project Card */
  .project-card {
    background: #f9f9f9; /* Light grey background */
    padding: 20px;
    border: 1px solid #e0e0e0;
    border-radius: 8px;
    text-decoration: none !important; /* Removes underline from the whole box */
    color: #333;
    transition: transform 0.2s, box-shadow 0.2s;
    height: 100%; /* Makes cards equal height */
    display: flex;
    flex-direction: column;
  }

  /* 3. Hover Effect */
  .project-card:hover {
    transform: translateY(-3px); /* Slight lift */
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    border-color: #333;
  }

  .project-card h3 {
    margin-top: 0;
    margin-bottom: 0.5rem;
    font-size: 1.2rem;
  }

  .project-card p {
    font-size: 0.9rem;
    color: #666;
    margin-bottom: 0;
  }

  .project-date {
    font-size: 0.75rem;
    text-transform: uppercase;
    letter-spacing: 1px;
    color: #999;
    margin-bottom: 0.5rem;
    display: block;
  }

  /* Mobile Responsive: Switch to 1 column on small screens */
  @media (max-width: 600px) {
    .project-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

Hi, I'm **Muthudinesh**.

I'm a Product Designer at Congruent. By day, I build robust enterprise applications. By night, I tinker with electronics and AI. I bridge the gap between "it looks good" and "it actually works."

---

## Works

<div class="project-grid">

  <a href="./project-1" class="project-card">
    <span class="project-date">Oct 2025</span>
    <h3>GPS Navigator</h3>
    <p>A minimalist pure navigation device built for delivery partners using ESP32.</p>
  </a>

  <a href="#" class="project-card">
    <span class="project-date">Sep 2025</span>
    <h3>Email System Design</h3>
    <p>Redesigning the HTML email template structure for better responsive behavior.</p>
  </a>

  <a href="#" class="project-card">
    <span class="project-date">Aug 2025</span>
    <h3>Figma to Code Agent</h3>
    <p>An AI experiment leveraging prompt engineering to automate handoffs.</p>
  </a>

  <a href="#" class="project-card">
    <span class="project-date">Jul 2025</span>
    <h3>Enterprise Design System</h3>
    <p>Building a robust UI kit for 401k record-keeping dashboards.</p>
  </a>

</div>
