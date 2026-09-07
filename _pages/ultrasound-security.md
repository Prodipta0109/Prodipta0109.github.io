---
layout: page
permalink: /research/ultrasound-security/
title: Improving Security of Systems Integrated in Ultrasound Devices
description: Contract-based method to scope security re-verification when ultrasound software modules update.
nav: false
---

<style>
.res-hero {
  border-left: 4px solid #5BA8A0;
  padding: 10px 18px;
  margin-bottom: 28px;
}
.res-hero .affil {
  font-size: 0.95em;
  opacity: 0.8;
}
.res-status-badge {
  display: inline-block;
  background: rgba(212,166,42,0.16);
  color: #D4A62A;
  border: 1px solid rgba(212,166,42,0.4);
  border-radius: 999px;
  padding: 4px 14px;
  font-size: 0.8em;
  font-weight: 600;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  margin-top: 10px;
}
.res-section {
  margin: 32px 0;
}
.res-section h2 {
  font-size: 1.15em;
  letter-spacing: 0.02em;
  border-bottom: 1px solid rgba(128,128,128,0.2);
  padding-bottom: 8px;
  margin-bottom: 16px;
}
.approach-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 14px;
}
.approach-card {
  background: rgba(128,128,128,0.06);
  border-radius: 12px;
  padding: 16px 18px;
  border: 1px solid rgba(128,128,128,0.12);
  box-shadow: 0 2px 8px rgba(0,0,0,0.06);
  transition: transform 0.15s ease;
}
.approach-card .step-num {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 24px;
  height: 24px;
  border-radius: 50%;
  background: rgba(91,168,160,0.2);
  color: #5BA8A0;
  font-weight: 700;
  font-size: 0.85em;
  margin-bottom: 8px;
}
.approach-card p {
  margin: 0;
  font-size: 0.95em;
}
.tools-pills {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}
.tool-pill {
  background: rgba(91,168,160,0.14);
  border: 1px solid rgba(91,168,160,0.35);
  color: inherit;
  border-radius: 999px;
  padding: 5px 14px;
  font-size: 0.85em;
}
.back-link {
  display: inline-block;
  margin-top: 36px;
  font-size: 0.9em;
  opacity: 0.85;
}
</style>

<div class="res-hero" markdown="1">
**Samsung R&D Institute Bangladesh** · *August 2026 – Present*
<div class="res-status-badge">Early Stage</div>
</div>

<div class="res-section" markdown="1">
## Overview

Different teams independently develop, test, and release the various software components integrated into an ultrasound machine — imaging, connectivity, authentication, storage. Each team validates its own module in isolation, but an update to one module can silently invalidate a security assumption another module relies on, since patient data across the system needs to stay tightly secured.
</div>

<div class="res-section" markdown="1">
## Approach

<div class="approach-grid" markdown="1">

<div class="approach-card" markdown="1">
<span class="step-num">1</span>

**Model the contracts**

Capture the security-relevant assumptions each module makes about its neighbors — data formats, authentication boundaries, access scope.
</div>

<div class="approach-card" markdown="1">
<span class="step-num">2</span>

**Detect impact at update time**

Build a method to identify, for any given code change, which of those modeled assumptions the change could affect.
</div>

<div class="approach-card" markdown="1">
<span class="step-num">3</span>

**Scope re-verification**

Re-test only the modules genuinely at risk from an update, instead of retesting the entire software stack every time.
</div>

</div>
</div>

<div class="res-section" markdown="1">
## Status

Framing the research question and reviewing related work in cross-component security testing, drawing on approaches from medical-device regulatory practice, service-oriented architecture regression testing, and automotive ECU impact analysis.
</div>

<div class="res-section" markdown="1">
## Tools

<div class="tools-pills" markdown="1">
<span class="tool-pill">CodeQL</span>
<span class="tool-pill">Semgrep</span>
<span class="tool-pill">NetworkX</span>
<span class="tool-pill">pydicom</span>
<span class="tool-pill">Syft</span>
<span class="tool-pill">CycloneDX</span>
</div>
</div>

[← Back to research](/research/) {: .back-link }