---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research focuses on developing, evaluating, and implementing human-centered healthcare technologies by integrating Human–Computer Interaction, Behavioural Science, Artificial Intelligence, and Digital Health.

<div class="research-grid">

{% for project in site.portfolio %}
  <div class="research-card">

    <a href="{{ project.url }}">
      <div class="research-image">
        {% if project.image %}
        <img src="{{ project.image }}" alt="{{ project.title }}">
        {% endif %}
      </div>

      <div class="research-content">
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
