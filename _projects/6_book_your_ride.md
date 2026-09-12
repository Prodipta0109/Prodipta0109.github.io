---
layout: page
title: Book Your Ride
description: Android bus ticketing with seat inventory kept consistent under concurrent booking requests. <span style="display:block;margin-top:8px;font-size:0.78em;font-weight:500;letter-spacing:0.06em;text-transform:uppercase;opacity:0.55;">2021</span>
img: assets/img/bus_booking.png
importance: 6
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
**University of Dhaka**, Dhaka, Bangladesh · 2021
</div>

## Overview

**Book Your Ride** is an Android application that digitizes searching, scheduling, and purchasing intercity bus tickets.

- **Concurrent seat inventory** — Seat state is held in a shared inventory model, with simultaneous reservations for the same seat resolved through Firebase transactions so no seat can be double-allocated.
- **Ticket booking and scheduling** — Users browse available schedules filtered by destination and travel date, then book against live seat availability.
- **Digital ticketing** — Digital ticket copies replace physical counter sales, accessible and presentable from the app.

**My contributions:** I designed the backend architecture and the seat inventory model, and handled its synchronization with the database and frontend.

<div class="links-list" markdown="1">
### 🔗 Important Links

- [Project Code](https://github.com/karmakersagar/Bus-Tickets)
</div>

## Skills

<table class="skills-table">
  <tr>
    <th>Technical</th>
    <td>Java, Firebase, Android Studio SDK</td>
  </tr>
  <tr>
    <th>Soft</th>
    <td>Project planning, team leadership, negotiation</td>
  </tr>
</table>
