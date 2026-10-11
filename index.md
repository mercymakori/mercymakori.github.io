---
layout: default
title: Home
description: Mercy Makori — History & Kiswahili teacher, trained in Kenyan Sign Language and inclusive education.
---
{% assign cv = site.data.cv %}

<section class="hero">
  <div class="page">
    <p class="hero-kicker">History &amp; Kiswahili Educator</p>
    <h1 class="hero-name">{{ cv.contact.name }}</h1>
    <p class="hero-tagline">{{ cv.contact.tagline }}</p>
    <div class="hero-actions">
      <a href="{{ '/about/' | relative_url }}" class="btn btn-primary">About me</a>
      <a href="{{ '/projects/' | relative_url }}" class="btn btn-secondary">My work</a>
    </div>
    <div class="hero-stats">
      <div class="hero-stat">
        <span class="hero-stat-num">B.Ed</span>
        <span class="hero-stat-label">KCA University, 2nd Class Upper</span>
      </div>
      <div class="hero-stat">
        <span class="hero-stat-num">CBE/CBC</span>
        <span class="hero-stat-label">Competency-based curriculum</span>
      </div>
      <div class="hero-stat">
        <span class="hero-stat-num">KSL</span>
        <span class="hero-stat-label">Kenyan Sign Language trained</span>
      </div>
    </div>
  </div>
</section>

<section class="section">
  <div class="page">
    <div class="section-head">
      <p class="kicker">Profile</p>
      <h2>What I do</h2>
    </div>
    <p class="lead">{{ cv.summary }}</p>
  </div>
</section>

<section class="section">
  <div class="page">
    <div class="section-head">
      <p class="kicker">Highlights</p>
      <h2>At a glance</h2>
    </div>
    <div class="projects-grid">
      <div class="project-card">
        <span class="badge">Teaching</span>
        <h3>History &amp; Kiswahili</h3>
        <p>Teaching both subjects across Junior and Senior School, with learner-centred lessons aligned to the Competency-Based Education framework.</p>
      </div>
      <div class="project-card">
        <span class="badge">Inclusion</span>
        <h3>Kenyan Sign Language</h3>
        <p>Certified in Kenyan Sign Language (Training of Trainers), with hands-on attachment experience at a school for the deaf and live interpretation.</p>
      </div>
      <div class="project-card">
        <span class="badge">Training</span>
        <h3>Trainer &amp; Facilitator</h3>
        <p>Trained NYOTA beneficiaries in social-emotional, business, and digital skills — certified Training of Trainers.</p>
      </div>
    </div>
  </div>
</section>
