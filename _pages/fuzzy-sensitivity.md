---
layout: page
permalink: /research/fuzzy-sensitivity/
title: Sensitivity Analysis with Fuzzy Sets
description: Identifying which inputs and rules drive fuzzy inference system robustness, applied to a noise-resilient movie recommendation system.
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
**LUCID Lab, University of Nottingham, UK** · Supervisor: Dr. Shaily Kabir · *October 2024 – March 2025*
<div class="res-status-badge">Research White Paper</div>
</div>

<div class="res-section" markdown="1">
## Overview

Identifying which input variables and fuzzy rules determine the robustness and reliability of a fuzzy inference system, and evaluating how effectively non-singleton fuzzy sets (NSFLSs) handle uncertainty as dataset noise increases — applied here to a real-world movie recommendation setting.
</div>

<div class="res-section" markdown="1">
## Approach

<div class="approach-grid" markdown="1">

<div class="approach-card" markdown="1">
<span class="step-num">1</span>

**System design**

Designed a non-singleton fuzzy set (NSFLS)-based movie recommendation system, using the MovieLens dataset as the underlying rating data.
</div>

<div class="approach-card" markdown="1">
<span class="step-num">2</span>

**Noise modeling**

Identified why review-based inputs used in movie recommendation are inherently uncertain, and constructed noisy versions of the dataset to test system robustness.
</div>

<div class="approach-card" markdown="1">
<span class="step-num">3</span>

**Comparative evaluation**

Compared NSFLS-based recommendation performance against basic collaborative filtering and type-1 (singleton) fuzzy-based recommendation systems under varying noise levels.
</div>

</div>
</div>

<div class="res-section" markdown="1">
## Outcomes

Results show the NSFLS-based recommendation system consistently outperforming both collaborative filtering and singleton (type-1) fuzzy approaches as noise increases, demonstrating non-singleton fuzzy sets as a robust way to handle uncertain, noisy movie ratings.

This work is documented as a research white paper: [*"Towards Improved Movie Recommendations via Handling of Input Uncertainty"*](https://prodipta0109.github.io/assets/pdf/Towards_Improved_Movie_Recommendations_via_Handling_of_Input_Uncertainty.pdf), co-authored with Tahmid Imtiaz, Dr. Shaily Kabir, and Dr. Christian Wagner.
</div>

<div class="res-section" markdown="1">
## Tools

<div class="tools-pills" markdown="1">
<span class="tool-pill">FuzzyR</span>
<span class="tool-pill">Explainable AI</span>
</div>
</div>

<a class="back-link" href="/research/">← Back to research</a>