---
layout: page
title: Library Management System
description: Normalized library database with referential integrity enforced through foreign key constraints. <span style="display:block;margin-top:8px;font-size:0.78em;font-weight:500;letter-spacing:0.06em;text-transform:uppercase;opacity:0.55;">2020</span>
img: assets/img/library_db.png
importance: 7
category: academic
---

<style>
.proj-meta {
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
.links-list {
  border-left: 4px solid #D4A62A;
  background: rgba(128,128,128,0.06);
  border-radius: 10px;
  padding: 16px 24px;
  margin: 20px 0;
}
.links-list ul {
  margin-bottom: 0;
}
</style>

<div class="proj-meta" markdown="1">
**University of Dhaka**, Dhaka, Bangladesh · 2020
</div>

## Overview

**Library Management System** is a normalized relational database designed to support the day-to-day management and operations of an institute's library.

- **Database design** — Structured the schema using normalization principles to eliminate redundancy across catalog and circulation records.
- **Referential integrity** — Enforced valid relationships across circulation records through foreign key constraints, so loans cannot reference nonexistent members or copies.
- **Views for common operations** — Created views abstracting the recurring queries behind routine library tasks.

**My contributions:** I designed the normalized schema, defined the foreign key constraints governing circulation records, and created the operational views.

<div class="links-list" markdown="1">
### 🔗 Important Links

- [Project Report](https://drive.google.com/file/d/1bTa6VOWWkC_5bIoF70mykPWHZsiMt_8O/view)
</div>

## Skills

<table class="skills-table">
  <tr>
    <th>Technical</th>
    <td>SQL, Oracle Database</td>
  </tr>
  <tr>
    <th>Soft</th>
    <td>Management system analysis, project planning, schema design and query development</td>
  </tr>
</table>
