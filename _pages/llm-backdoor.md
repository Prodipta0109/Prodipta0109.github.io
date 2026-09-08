---
layout: page
permalink: /research/llm-backdoor/
title: Backdoor Attacks in Large Language Model Reasoning
description: Investigating a novel backdoor attack targeting the reasoning process of large language models.
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
<div class="res-status-badge">Under Review — USENIX Security '27</div>
</div>

<div class="res-section" markdown="1">
## Overview

Investigating how the reasoning process of large language models can be compromised. The work combines chain-of-thought analysis with trigger-injection techniques to identify where reasoning chains are vulnerable and how corrupted intermediate steps propagate to final answers.
</div>

<div class="res-section" markdown="1">
## Approach

<div class="approach-grid" markdown="1">

<div class="approach-card" markdown="1">
<span class="step-num">1</span>

**Attack design**

Proposed a novel backdoor attack targeting the reasoning process of large language models.
</div>

<div class="approach-card" markdown="1">
<span class="step-num">2</span>

**Training pipeline**

Designed the training process used to produce the corrupted model.
</div>

<div class="approach-card" markdown="1">
<span class="step-num">3</span>

**Evaluation**

Performed intensive evaluation against prior work, and tested the robustness of the proposed attack against state-of-the-art defenses.
</div>

<div class="approach-card" markdown="1">
<span class="step-num">4</span>

**Writing & organization**

Helped organize the paper's structure and contributed to writing.
</div>

</div>
</div>

<div class="res-section" markdown="1">
## Status

One paper is currently under review at **Cycle-1, USENIX Security '27**.
</div>

<div class="res-section" markdown="1">
## Tools

<div class="tools-pills" markdown="1">
<span class="tool-pill">Python</span>
<span class="tool-pill">PyTorch</span>
<span class="tool-pill">Hugging Face Transformers</span>
</div>
</div>

<a class="back-link" href="/research/">← Back to research</a>