---
layout: page
permalink: /experience/cloud-solutions/
title: Cloud Solutions × SonoSync — Samsung Medison
description: Real-time ultrasound streaming and remote machine control, built without ffmpeg.
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
**Samsung R&D Institute Bangladesh** · SRBD Medical Solution Group · *March 2024 – February 2025*
</div>

## Overview

My first project at Samsung, working with the R&D team on Samsung Medison's Cloud Solutions — a collaboration with **SonoSync** to bring real-time ultrasound streaming to devices outside the scanning room.

The problem it solves is a practical one in clinical settings. An ultrasound examination happens at the machine, but the people who need to see it — a consulting specialist, a supervising physician, a remote colleague — are often somewhere else entirely. The system streams the live scan to a doctor's desktop or other device as it happens, so distance stops being a constraint on who can observe an examination.

The scope went beyond viewing. We integrated the machine's engines into the cloud, so medical staff can operate the ultrasound device's components and use its features remotely, without being physically present in the same room as the hardware.

## What I did

- Served as the **streaming technology specialist** on the team, responsible for publishing the generated ultrasound stream to the web in real time
- Built a custom application that removed the project's dependency on ffmpeg for reading and displaying the stream
- Implemented **double buffering** using **DirectShow** and **Media Foundation** to control the frame pipeline directly
- Worked on the cloud integration that allows remote control of ultrasound machine components and features
- Contributed to the real-time transport layer connecting the machine to remote clients

## The ffmpeg problem

<div class="callout" markdown="1">
The original pipeline relied on ffmpeg to read and display the generated stream. In a clinical context, that dependency carried real costs — added latency, licensing complications, and limited control over buffering behaviour at exactly the point where dropped frames matter most.
</div>

Replacing it meant building an application that reads and renders the stream directly, with double buffering implemented through DirectShow and Media Foundation. Removing ffmpeg from the pipeline eliminated the licensing and latency overhead, and put frame handling under our own control rather than behind a third-party abstraction.

## Skills

<table class="skills-table">
  <tr>
    <th>Technical</th>
    <td>Windows application development, computer networking, real-time transport protocols, C++, C#, Python, JavaScript, machine learning, Docker, cloud solutions using AWS and Azure, FFmpeg, MediaMTX, WebRTC, libdatachannel, named pipes</td>
  </tr>
  <tr>
    <th>Soft</th>
    <td>Communication, negotiation, time management, task and responsibility management, teamwork, collaboration, continuous self-improvement</td>
  </tr>
</table>

[← Back to experience](/experience/)
