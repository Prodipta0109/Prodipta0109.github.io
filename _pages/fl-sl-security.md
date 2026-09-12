---
layout: page
permalink: /research/fl-sl-security/
title: Security Analysis of Federated Learning and Split Learning
description: Transferability of attacks and defenses between federated learning and split learning.
nav: false
---

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