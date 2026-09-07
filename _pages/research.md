---
layout: page
permalink: /research/
title: research
description: Security of learning systems, explainable fuzzy inference, and medical imaging.
nav: true
nav_order: 2
---

<style>
.research-card {
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
.research-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 18px rgba(0,0,0,0.25);
}
.research-card img.thumb {
  width: 90px !important;
  height: 90px !important;
  min-width: 90px !important;
  max-width: 90px !important;
  object-fit: contain !important;
  background: #fff;
  border-radius: 8px;
  padding: 6px;
  flex-shrink: 0;
  display: block;
}
.research-card .card-body {
  min-width: 0;
  flex: 1;
}
.research-card h3 {
  margin-bottom: 6px;
}
.research-card h3 a {
  color: #5BA8A0;
  text-decoration: none;
}
.research-card .meta {
  font-size: 0.85em;
  opacity: 0.75;
  margin-bottom: 10px;
}
.research-card .summary {
  opacity: 0.9;
  margin-bottom: 0;
}
/* makes the whole card clickable even though only the title text is a real link */
.research-card h3 a::after {
  content: "";
  position: absolute;
  inset: 0;
}
@media (max-width: 600px) {
  .research-card img.thumb {
    width: 56px !important;
    height: 56px !important;
    min-width: 56px !important;
    max-width: 56px !important;
  }
}
</style>

<div class="research-card" markdown="1">
<img class="thumb" src="/assets/img/research/KSU_logo.png" alt="Kennesaw State University logo">
<div class="card-body" markdown="1">
### [Backdoor Attacks in Large Language Model Reasoning](/research/llm-backdoor/)
<div class="meta">Kennesaw State University, USA · Supervisor: <a href="https://honghuixuhenry.github.io/index.html">Dr. Honghui Xu</a> · July 2026 – Present</div>
<p class="summary">Investigating how the reasoning process of large language models can be compromised, combining chain-of-thought analysis with trigger-injection techniques (<em>one paper is currently under review at Cycle-1, USENIX Security '27</em>).</p>
</div>
</div>

<div class="research-card" markdown="1">
<img class="thumb" src="/assets/img/research/Samsung_logo.png" alt="Samsung R&D Institute Bangladesh logo">
<div class="card-body" markdown="1">
### [Improving security of the system integrated in ultrasound devices](/research/ultrasound-3d-imaging/)
<div class="meta">Samsung R&D Institute Bangladesh · August 2026 – Present</div>
<p class="summary">Developing a contract-based method to automatically scope security re-verification to only the modules an update could affect, instead of retesting the entire ultrasound software stack.</p>
</div>
</div>

<div class="research-card" markdown="1">
<img class="thumb" src="/assets/img/research/UoN.png" alt="University of Nottingham logo">
<div class="card-body" markdown="1">
### [Sensitivity Analysis with Fuzzy Sets](/research/fuzzy-sensitivity/)
<div class="meta">LUCID Lab, University of Nottingham, UK · Supervisor: <a href="https://scholar.google.com/citations?user=9pixW4wAAAAJ&hl=en">Dr. Shaily Kabir</a> · October 2024 – March 2025</div>
<p class="summary">Identifying which input variables and fuzzy rules determine the robustness and reliability of a fuzzy inference system as noise in the dataset of a system increases.</p>
</div>
</div>

<div class="research-card" markdown="1">
<img class="thumb" src="/assets/img/research/DU_logo.png" alt="University of Dhaka logo">
<div class="card-body" markdown="1">
### [Interval Type-2 Fuzzy Sets: Behaviour and Performance](/research/interval-type2-fuzzy/)
<div class="meta">University of Dhaka · March 2023 – January 2024</div>
<p class="summary">Designed the Interval Creation Approach (ICA), a method for constructing interval type-2 fuzzy sets from type-1 fuzzy set, leading to a first-author paper at FUZZ-IEEE 2024, as a part of IEEE WCCI 2024.</p>
</div>
</div>
