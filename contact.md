---
layout: default
title: Contact
description: Contact Mercy Makori.
permalink: /contact/
---
{% assign cv = site.data.cv %}
<section class="section"><div class="page"><div class="section-head"><p class="kicker">Contact</p><h1>Get in touch</h1></div><div class="article-body" style="margin-top:24px"><p><strong>{{ cv.contact.name }}</strong> — {{ cv.contact.title }}</p><p>Location: {{ cv.contact.location }}</p><p>Phone: <a href="tel:{{ cv.contact.phone }}">{{ cv.contact.phone }}</a> · TSC: {{ cv.contact.tsc }}</p><p>Email: <a href="mailto:{{ cv.contact.email }}">{{ cv.contact.email }}</a></p></div></div></section>
