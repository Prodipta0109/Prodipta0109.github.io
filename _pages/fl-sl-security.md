---
layout: page
permalink: /research/fl-sl-security/
title: Security Analysis of Federated Learning and Split Learning
description: Transferability of attacks and defenses between federated learning and split learning.
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
  line-height: 2.6;
}
.tool-pill {
  display: inline-block;
  background: rgba(91,168,160,0.14);
  border: 1px solid rgba(91,168,160,0.35);
  color: inherit;
  border-radius: 999px;
  padding: 5px 14px;
  font-size: 0.85em;
  margin: 4px 4px 4px 0;
}
.tool-pill.soft {
  background: rgba(212,166,42,0.14);
  border-color: rgba(212,166,42,0.35);
}
.back-link {
  display: inline-block;
  margin-top: 36px;
  font-size: 0.9em;
  opacity: 0.85;
}
</style>

<div class="res-hero" markdown="1">
**Kennesaw State University, USA** · Supervisor: Dr. Honghui Xu · *July 2026 – Present*
<div class="res-status-badge">In Preparation — IEEE S&P 2027</div>
</div>

<div class="res-section" markdown="1">
## Overview

Federated learning and split learning both train models without centralizing raw data, but they distribute computation differently — federated learning keeps the full model on every client, while split learning cuts the network and shares intermediate activations instead. Attacks and defenses have largely been developed within each paradigm separately, and it is not established which results carry across. This work asks where the architectural difference invalidates the assumptions an attack or a defense depends on.
</div>

<div class="res-section" markdown="1">
## Approach

<div class="approach-grid" markdown="1">

<div class="approach-card" markdown="1">
<span class="step-num">1</span>

**Systematize the landscape**

Catalog attack patterns and defense mechanisms across both paradigms, identifying the threat model each was designed against.
</div>

<div class="approach-card" markdown="1">
<span class="step-num">2</span>

**Test generalizability**

Evaluate model inversion, membership inference, and gradient leakage against differential privacy and secure aggregation in both settings, measuring where effectiveness holds and where it collapses.
</div>

<div class="approach-card" markdown="1">
<span class="step-num">3</span>

**Establish transferability criteria**

Define the theoretical grounds and evaluation metrics for when a result in one paradigm should be expected to hold in the other.
</div>

</div>
</div>

<div class="res-section" markdown="1">
## Status

A **Systematization of Knowledge (SoK)** paper is in preparation, targeting the IEEE Symposium on Security and Privacy (Oakland) 2027.
</div>

<div class="res-section" markdown="1">
## Tools

<div class="tools-pills" markdown="1">
<span class="tool-pill">Python</span>
<span class="tool-pill">PyTorch</span>
<span class="tool-pill">FedAvg</span>
<span class="tool-pill">FedProx</span>
<span class="tool-pill soft">Differential Privacy</span>
<span class="tool-pill soft">Secure Aggregation</span>
</div>
</div>

<a class="back-link" href="/research/">← Back to research</a>