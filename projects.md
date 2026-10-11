---
layout: default
title: Work
description: Mercy Makori's teaching experience — history, Kiswahili, sign language, and youth training.
permalink: /projects/
---
{% assign cv = site.data.cv %}
<div class="section"><div class="page">
<div class="section-head"><p class="kicker">Work</p><h1>Experience</h1></div>
<p class="lead">History &amp; Kiswahili educator with experience across Junior &amp; Senior School, inclusive sign-language instruction, and youth facilitation.</p>
<div style="margin-top:28px">
{% for item in cv.experience %}
<div class="cv-entry" style="margin-bottom:28px;padding-bottom:20px;border-bottom:1px solid var(--border-subtle)">
<div class="cv-entry-head"><span class="cv-entry-title">{{ item.role }}</span><span class="cv-entry-date">{{ item.period }}</span></div>
<p class="cv-entry-sub">{{ item.org }} · {{ item.location }}</p>
{% if item.level %}<p style="font-size:13px;color:var(--text-3);margin:4px 0">Level: {{ item.level }}</p>{% endif %}
<ul style="margin:8px 0 0 18px;padding-left:6px;font-size:15px;line-height:1.55;color:var(--text-2)">
{% for b in item.bullets %}<li>{{ b }}</li>{% endfor %}
</ul>
</div>
{% endfor %}
</div>
</div></div>
