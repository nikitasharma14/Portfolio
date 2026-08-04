---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

My research focuses on developing, evaluating, and implementing human-centered healthcare technologies by integrating Human–Computer Interaction, Behavioural Science, Artificial Intelligence, and Digital Health.

<h2>Projects detected: {{ site.portfolio.size }}</h2>

{% for project in site.portfolio %}

<p>
<strong>Title:</strong> {{ project.title }} <br>
<strong>URL:</strong> {{ project.url }}
</p>

{% endfor %}
