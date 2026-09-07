---
layout: page
permalink: /experience/cardiac-tee/
title: Cardiac TEE Rendering × 5D Viewer
description: Samsung R&D Institute Bangladesh · April 2026 – Present
nav: false
---

<style>
.exp-meta {
  font-size: 0.9em;
  opacity: 0.75;
  border-left: 4px solid #5BA8A0;
  padding: 8px 16px;
  margin-bottom: 24px;
}
.skills-table {
  width: 100%;
  border-collapse: separate;
  border-spacing: 0;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 14px rgba(0,0,0,0.15);
  margin-top: 12px;
}
.skills-table th {
  background: rgba(91,168,160,0.18);
  padding: 12px 18px;
  text-align: left;
  font-size: 0.9em;
  letter-spacing: 0.04em;
  text-transform: uppercase;
  width: 180px;
  vertical-align: top;
  border-bottom: 1px solid rgba(128,128,128,0.15);
}
.skills-table td {
  background: rgba(128,128,128,0.06);
  padding: 12px 18px;
  border-bottom: 1px solid rgba(128,128,128,0.15);
}
.skills-table tr:last-child th,
.skills-table tr:last-child td {
  border-bottom: none;
}
</style>

<div class="exp-meta" markdown="1">
**Samsung R&D Institute Bangladesh** · *April 2026 – Present*
</div>

## Overview

Leading rendering and UI optimization for the **5D Viewer** in Samsung Medison's cardiac transesophageal echocardiography (TEE) product. The 5D Viewer renders live volumetric ultrasound data of a beating heart, reconstructed directly from real-time data transmitted by the transducer. That combination — volumetric, live, and medical-grade — makes performance a hard constraint rather than a nice-to-have: clinicians need the rendered volume to respond immediately as they adjust the probe and the view. The 5D Viewer also serves as the testbed for our rendering engine's capability more broadly.

The project centers on rendering different types of GDI objects onto both static and real-time 3D volumes, and aligning operations on the 2D plane cut from different locations within the 3D volume.

## What I work on

### Rendering and interaction

- Optimizing the UI design of the viewer for responsiveness under continuous volume updates
- Implementing the interaction layer that handles actions performed on rendered objects — rotation, slicing, and repositioning within the volume
- Sole owner of optimizing the 5D Viewer UI

### Internationalization

- Implementing support for rendering labels in all languages worldwide

### 4D Markers and Calipers

- Designing and implementing **4D markers** — points placed within the volume to indicate different conditions
- Designing and implementing **4D calipers** — similar to markers, but used to indicate covered area using different shapes: lines, angles, polygons, and splines (both closed and open)
- For both features: built using **DirectX**, spanning the UI component, the communication pipeline between the rendering engine and the UI, the backend implementation for rendering the shapes, and testing on the ultrasound machine itself

## Skills

<table class="skills-table">
  <tr>
    <th>Technical</th>
    <td>C#, C++, HLSL, DirectX, real-time 3D rendering, volumetric rendering, GDI, UI/UX optimization, internationalization, pipeline design</td>
  </tr>
  <tr>
    <th>Soft</th>
    <td>Ownership, performance-driven design, cross-team testing, medical-device constraints</td>
  </tr>
</table>

[← Back to experience](/experience/)