---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

My research focuses on developing, evaluating, and implementing human-centered healthcare technologies by integrating Human–Computer Interaction, Behavioural Science, Artificial Intelligence, and Digital Health.

<div class="research-grid">

{% for project in site.portfolio %}

<h2>{{ project.title }}</h2>

<p>{{ project.url }}</p>

{% endfor %}

</div>
