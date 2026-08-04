---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

My research focuses on developing, evaluating, and implementing human-centered healthcare technologies by integrating Human–Computer Interaction, Behavioural Science, Artificial Intelligence, and Digital Health.

<p>TEST START</p>

Number of projects: {{ site.portfolio | size }}

{% for project in site.portfolio %}

<p>PROJECT: {{ project.title }}</p>

{% endfor %}

<p>TEST END</p>
