---
layout: page
permalink: /repositories/
title: repositories
description: A few of my public repositories, including collaborative projects.
nav: true
nav_order: 4
---

<style>
.repo-section-title {
  font-size: 1.3em;
  margin: 36px 0 4px;
}
.repo-section-sub {
  font-size: 0.88em;
  opacity: 0.7;
  margin-bottom: 18px;
}
.repo-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 18px;
  justify-content: center;
}
.repo-card {
  border-left: 4px solid #5BA8A0;
  background: rgba(128,128,128,0.06);
  border-radius: 12px;
  padding: 14px;
  box-shadow: 0 4px 14px rgba(0,0,0,0.15);
  max-width: 420px;
  width: 100%;
  display: block;
  transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
  text-decoration: none !important;
}
.repo-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 22px rgba(0,0,0,0.28);
  border-left-color: #D4A62A;
}
.repo-card img {
  width: 100%;
  display: block;
  border-radius: 6px;
}
.repo-card.user-card {
  border-left-color: #D4A62A;
  max-width: 560px;
}
.repo-card.user-card:hover {
  border-left-color: #5BA8A0;
}
/* fade-in on load */
.repo-card {
  animation: repoFadeIn 0.5s ease both;
}
.repo-grid .repo-card:nth-child(1) { animation-delay: 0.05s; }
.repo-grid .repo-card:nth-child(2) { animation-delay: 0.12s; }
.repo-grid .repo-card:nth-child(3) { animation-delay: 0.19s; }
.repo-grid .repo-card:nth-child(4) { animation-delay: 0.26s; }
.repo-grid .repo-card:nth-child(5) { animation-delay: 0.33s; }
@keyframes repoFadeIn {
  from { opacity: 0; transform: translateY(12px); }
  to   { opacity: 1; transform: translateY(0); }
}
@media (max-width: 600px) {
  .repo-card, .repo-card.user-card { max-width: 100%; }
}
</style>

<div class="repo-section-title">GitHub profile</div>
<div class="repo-section-sub">An overview of my activity on GitHub.</div>

<div class="repo-grid">
  <a class="repo-card user-card" href="https://github.com/Prodipta0109" target="_blank">
    <img class="only-dark" src="https://github-stats-extended.vercel.app/api?username=Prodipta0109&theme=dark&show_icons=true&hide_border=true&v={{ site.time | date: '%s' }}" alt="Prodipta0109 GitHub stats">
    <img class="only-light" src="https://github-stats-extended.vercel.app/api?username=Prodipta0109&theme=default&show_icons=true&hide_border=true&v={{ site.time | date: '%s' }}" alt="Prodipta0109 GitHub stats">
  </a>
</div>

<div class="repo-section-title">Repositories</div>
<div class="repo-section-sub">Personal and collaborative projects — click any card to open it on GitHub.</div>

<div class="repo-grid">
  <a class="repo-card" href="https://github.com/Prodipta0109/Prodipta0109.github.io" target="_blank">
    <img class="only-dark" src="https://github-stats-extended.vercel.app/api/pin/?username=Prodipta0109&repo=Prodipta0109.github.io&theme=dark&show_owner=true&description_lines_count=2&v={{ site.time | date: '%s' }}" alt="Prodipta0109.github.io">
    <img class="only-light" src="https://github-stats-extended.vercel.app/api/pin/?username=Prodipta0109&repo=Prodipta0109.github.io&theme=default&show_owner=true&description_lines_count=2&v={{ site.time | date: '%s' }}" alt="Prodipta0109.github.io">
  </a>

  <a class="repo-card" href="https://github.com/Prodipta0109/Basic-Split-Learning-Architecture-for-SafeSplit" target="_blank">
    <img class="only-dark" src="https://github-stats-extended.vercel.app/api/pin/?username=Prodipta0109&repo=Basic-Split-Learning-Architecture-for-SafeSplit&theme=dark&show_owner=true&description_lines_count=2&v={{ site.time | date: '%s' }}" alt="SafeSplit Split Learning">
    <img class="only-light" src="https://github-stats-extended.vercel.app/api/pin/?username=Prodipta0109&repo=Basic-Split-Learning-Architecture-for-SafeSplit&theme=default&show_owner=true&description_lines_count=2&v={{ site.time | date: '%s' }}" alt="SafeSplit Split Learning">
  </a>

  <a class="repo-card" href="https://github.com/dsPartho/Gardening-Tukitaki" target="_blank">
    <img class="only-dark" src="https://github-stats-extended.vercel.app/api/pin/?username=dsPartho&repo=Gardening-Tukitaki&theme=dark&show_owner=true&description_lines_count=2&v={{ site.time | date: '%s' }}" alt="Gardening-Tukitaki">
    <img class="only-light" src="https://github-stats-extended.vercel.app/api/pin/?username=dsPartho&repo=Gardening-Tukitaki&theme=default&show_owner=true&description_lines_count=2&v={{ site.time | date: '%s' }}" alt="Gardening-Tukitaki">
  </a>

  <a class="repo-card" href="https://github.com/shakifCSEDU/Find-Your-Doctor" target="_blank">
    <img class="only-dark" src="https://github-stats-extended.vercel.app/api/pin/?username=shakifCSEDU&repo=Find-Your-Doctor&theme=dark&show_owner=true&description_lines_count=2&v={{ site.time | date: '%s' }}" alt="Find-Your-Doctor">
    <img class="only-light" src="https://github-stats-extended.vercel.app/api/pin/?username=shakifCSEDU&repo=Find-Your-Doctor&theme=default&show_owner=true&description_lines_count=2&v={{ site.time | date: '%s' }}" alt="Find-Your-Doctor">
  </a>

  <a class="repo-card" href="https://github.com/karmakersagar/Bus-Tickets" target="_blank">
    <img class="only-dark" src="https://github-stats-extended.vercel.app/api/pin/?username=karmakersagar&repo=Bus-Tickets&theme=dark&show_owner=true&description_lines_count=2&v={{ site.time | date: '%s' }}" alt="Bus-Tickets">
    <img class="only-light" src="https://github-stats-extended.vercel.app/api/pin/?username=karmakersagar&repo=Bus-Tickets&theme=default&show_owner=true&description_lines_count=2&v={{ site.time | date: '%s' }}" alt="Bus-Tickets">
  </a>
</div>
