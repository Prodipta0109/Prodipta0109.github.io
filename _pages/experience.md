---
layout: page
permalink: /experience/
title: experience
description: Engineering work at Samsung R&D Institute Bangladesh.
nav: true
nav_order: 3
---

<style>
.experience-card {
  position: relative;
  display: flex !important;
  flex-direction: row !important;
  gap: 20px;
  align-items: flex-start;
  border-left: 4px solid #5BA8A0;
  background: rgba(128,128,128,0.06);
  border-radius: 10px;
  padding: 22px 26px;
  margin-bottom: 20px;
  box-shadow: 0 4px 14px rgba(0,0,0,0.15);
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}
.experience-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 18px rgba(0,0,0,0.25);
}
.experience-card img.thumb {
  width: 200px !important;
  height: 160px !important;
  min-width: 200px !important;
  max-width: 200px !important;
  object-fit: contain !important;
  background: #fff;
  border-radius: 8px;
  padding: 8px;
  flex-shrink: 0;
  display: block;
}
.experience-card .card-body {
  min-width: 0;
  flex: 1;
}
.experience-card h3 {
  margin-bottom: 6px;
}
.experience-card h3 a {
  color: #5BA8A0;
  text-decoration: none;
}
.experience-card .meta {
  font-size: 0.85em;
  opacity: 0.75;
  margin-bottom: 10px;
}
.experience-card .summary {
  opacity: 0.9;
  margin-bottom: 0;
}
/* makes the whole card clickable even though only the title text is a real link */
.experience-card h3 a::after {
  content: "";
  position: absolute;
  inset: 0;
}
@media (max-width: 600px) {
  .experience-card img.thumb {
    width: 130px !important;
    height: 105px !important;
    min-width: 130px !important;
    max-width: 130px !important;
  }
}
</style>

<div class="experience-card" markdown="1">
<img class="thumb" src="/assets/img/experience/5Dviewer_logo.png" alt="5D Viewer">
<div class="card-body" markdown="1">
### [Cardiac TEE Rendering & Optimization](/experience/cardiac-tee/)
<div class="meta">Samsung R&D Institute Bangladesh · April 2026 – Present</div>
<p class="summary">Leading UI optimization and the interaction layer for a 5D Viewer rendering live volumetric cardiac ultrasound data.</p>
</div>
</div>

<div class="experience-card" markdown="1">
<img class="thumb" src="/assets/img/experience/HelloMom_logo.png" alt="HelloMom">
<div class="card-body" markdown="1">
### [Cardiovascular Workstation](/experience/cardiovascular-workstation/)
<div class="meta">Samsung R&D Institute Bangladesh · March 2025 – March 2026</div>
<p class="summary">Full-stack work on a Windows and web workstation for cardiovascular ultrasound — UI, backend, database, and on-premises deployment.</p>
</div>
</div>

<div class="experience-card" markdown="1">
<img class="thumb" src="/assets/img/experience/Sonosync_logo.png" alt="SonoSync">
<div class="card-body" markdown="1">
### [Cloud Solutions — Medison](/experience/cloud-solutions/)
<div class="meta">Samsung R&D Institute Bangladesh · January 2024 – February 2025</div>
<p class="summary">Real-time ultrasound streaming to the web, removing an ffmpeg dependency by building a custom double-buffered streaming pipeline.</p>
</div>
</div>
