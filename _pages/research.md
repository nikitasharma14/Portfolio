---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

Below are selected research projects that reflect my transdisciplinary research in healthcare.

<div class="research-grid">

{% for project in site.portfolio %}

<div class="research-card">

<a href="{{ project.url }}">

{% if project.image %}
<img src="{{ project.image }}" alt="{{ project.title }}">
{% endif %}

<div class="research-card-content">

<h3>{{ project.title }}</h3>

{% if project.skills %}
<div class="skill-tags">

{% for skill in project.skills %}
<span>{{ skill }}</span>
{% endfor %}

</div>
{% endif %}

</div>

</a>

</div>

{% endfor %}

</div>
