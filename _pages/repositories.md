---
layout: page
permalink: /repositories/
title: repositories
description: Personal and collaborative work on GitHub.
nav: true
nav_order: 4
---

<style>
.repo-heading {
  font-size: 1.1em;
  font-weight: 500;
  margin: 30px 0 2px;
}
.repo-subheading {
  font-size: 0.86em;
  opacity: 0.7;
  margin-bottom: 14px;
}
.repo-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 14px;
}
.repo-card {
  border: 0.5px solid rgba(128,128,128,0.35);
  border-radius: 12px;
  padding: 10px;
  max-width: 420px;
  width: 100%;
  display: block;
  text-decoration: none !important;
  transition: border-color 0.18s ease;
}
.repo-card:hover {
  border-color: rgba(128,128,128,0.7);
}
.repo-card img {
  width: 100%;
  display: block;
  border-radius: 6px;
}
.repo-card.user-card {
  max-width: 560px;
}
@media (max-width: 600px) {
  .repo-card, .repo-card.user-card { max-width: 100%; }
}
</style>

<div class="repo-heading">GitHub profile</div>
<div class="repo-subheading">An overview of my activity on GitHub.</div>

<div class="repo-grid">
  <a class="repo-card user-card" href="https://github.com/Prodipta0109" target="_blank">
    <img class="only-dark" src="https://github-stats-extended.vercel.app/api?username=Prodipta0109&theme=dark&show_icons=true&hide_border=true&v={{ site.time | date: '%s' }}" alt="Prodipta0109 GitHub stats">
    <img class="only-light" src="https://github-stats-extended.vercel.app/api?username=Prodipta0109&theme=default&show_icons=true&hide_border=true&v={{ site.time | date: '%s' }}" alt="Prodipta0109 GitHub stats">
  </a>
</div>

<div class="repo-heading">Own work</div>
<div class="repo-subheading">Repositories I created and maintain.</div>

<div class="repo-grid">
  <a class="repo-card" href="https://github.com/Prodipta0109/Prodipta0109.github.io" target="_blank">
    <img class="only-dark" src="https://github-stats-extended.vercel.app/api/pin/?username=Prodipta0109&repo=Prodipta0109.github.io&theme=dark&show_owner=true&description_lines_count=2&v={{ site.time | date: '%s' }}" alt="Prodipta0109.github.io">
    <img class="only-light" src="https://github-stats-extended.vercel.app/api/pin/?username=Prodipta0109&repo=Prodipta0109.github.io&theme=default&show_owner=true&description_lines_count=2&v={{ site.time | date: '%s' }}" alt="Prodipta0109.github.io">
  </a>

  <a class="repo-card" href="https://github.com/Prodipta0109/Basic-Split-Learning-Architecture-for-SafeSplit" target="_blank">
    <img class="only-dark" src="https://github-stats-extended.vercel.app/api/pin/?username=Prodipta0109&repo=Basic-Split-Learning-Architecture-for-SafeSplit&theme=dark&show_owner=true&description_lines_count=2&v={{ site.time | date: '%s' }}" alt="Basic Split Learning Architecture for SafeSplit">
    <img class="only-light" src="https://github-stats-extended.vercel.app/api/pin/?username=Prodipta0109&repo=Basic-Split-Learning-Architecture-for-SafeSplit&theme=default&show_owner=true&description_lines_count=2&v={{ site.time | date: '%s' }}" alt="Basic Split Learning Architecture for SafeSplit">
  </a>
</div>

<div class="repo-heading">Collaborative</div>
<div class="repo-subheading">Team projects I contributed to.</div>

<div class="repo-grid">
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
