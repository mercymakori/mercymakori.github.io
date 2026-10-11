---
layout: default
title: About
description: About Mercy Makori — History & Kiswahili teacher trained in Kenyan Sign Language and inclusive education.
permalink: /about/
---
{% assign cv = site.data.cv %}

<section class="section">
  <div class="page">
    <div class="section-head">
      <p class="kicker">About</p>
      <h1>About me</h1>
    </div>
    <div class="article-body" style="margin-top:24px">
      <p>{{ cv.summary }}</p>
    </div>
  </div>
</section>

<section class="section">
  <div class="page">
    <div class="section-head">
      <p class="kicker">Education</p>
      <h2>Education &amp; training</h2>
    </div>
    <div class="article-body" style="margin-top:24px">
      {% for e in cv.education %}
      <div class="cv-entry">
        <div class="cv-entry-head">
          <span class="cv-entry-title">{{ e.qualification }}</span>
          <span class="cv-entry-date">{{ e.period }}</span>
        </div>
        <p class="cv-entry-sub">{{ e.institution }}</p>
        {% if e.detail %}<p class="cv-entry-detail">{{ e.detail }}</p>{% endif %}
      </div>
      {% endfor %}
    </div>
  </div>
</section>

<section class="section">
  <div class="page">
    <div class="section-head">
      <p class="kicker">Strengths</p>
      <h2>Core competencies</h2>
    </div>
    <div class="chip-grid">
      {% for c in cv.competencies %}
      <span class="chip">{{ c }}</span>
      {% endfor %}
    </div>
  </div>
</section>

<section class="section">
  <div class="page">
    <div class="section-head">
      <p class="kicker">Credentials</p>
      <h2>Certifications &amp; languages</h2>
    </div>
    <div class="article-body" style="margin-top:24px">
      <h3>Certifications</h3>
      <ul>
        {% for c in cv.certifications %}<li>{{ c }}</li>{% endfor %}
      </ul>
      <h3>Languages</h3>
      <ul>
        {% for l in cv.languages %}<li>{{ l }}</li>{% endfor %}
      </ul>
    </div>
  </div>
</section>
