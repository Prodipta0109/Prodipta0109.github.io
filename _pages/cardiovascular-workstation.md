---
layout: page
permalink: /experience/cardiovascular-workstation/
title: Cardiovascular Workstation × HelloMom
description: Full-stack development of a DICOM-based imaging platform and its companion app backbone.
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
.callout {
  border-left: 4px solid #D4A62A;
  background: rgba(128,128,128,0.06);
  border-radius: 10px;
  padding: 16px 24px;
  margin: 20px 0;
}
.callout p:last-child { margin-bottom: 0; }
</style>

<div class="exp-meta" markdown="1">
**Samsung R&D Institute Bangladesh** · SRBD Medical Solution Group · *March 2025 – March 2026*
</div>

## Overview

**HelloMom** is Samsung Medison's companion application for expecting parents. It wirelessly receives fetal ultrasound images and growth records from the ultrasound machine, and gives parents a place to keep a pregnancy diary and appointment reminders. It is built for keepsake and tracking purposes rather than medical diagnosis.

We built a server to store and fetch HelloMom's images in an organized way, forming the backbone behind the app. The core requirement was to fetch images from the ultrasound machine in **DICOM** format and organise them according to the metadata tags embedded in those files — turning raw clinical output into something a companion app can meaningfully present.

I worked across the full stack on this project, which is unusual for medical device work and was the most instructive part of it. Constraints at the UI layer and constraints at the database layer inform each other far more directly here than they do in typical web development.

## What I did

### Storage and deployment

- Solely implemented the **on-premises storage** version end to end using **IIS Windows Server**, alongside the cloud-based option
- Tested and successfully integrated the deployment across both **SRBD** and **Samsung Medison HQ** in Seoul, South Korea
- Deployed and configured the resulting system in an on-premises hospital environment

### Interface and documentation

- Designed and implemented the complete **UI component set** for both the Windows application and the web version
- Authored the accompanying documentation for the interface layer

### Backend and access control

- Designed and implemented the backend for **role-based file management and access**, covering doctors, administrators, and general users
- Architected the database management design underpinning it

### Authentication

- Designed and implemented the login and sign-up module in full — both backend and frontend
- Incorporated **Google OAuth 2.0** authentication
- Built in **single sign-on** so the system can serve other Samsung Medison applications in future, not just this one

### Team

- Mentored interns joining the team

## Skills

<table class="skills-table">
  <tr>
    <th>Technical</th>
    <td>React, WPF, .NET, IIS Windows Server, DICOM, Google OAuth 2.0, single sign-on, networking, database design</td>
  </tr>
  <tr>
    <th>Soft</th>
    <td>Teamwork, intern mentoring, leadership, ownership, cross-site collaboration, technical documentation</td>
  </tr>
</table>

[← Back to experience](/experience/)