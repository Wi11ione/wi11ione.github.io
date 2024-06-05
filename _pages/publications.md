---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my published articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

# Safety Critical Scenario Generation

{% assign paper1 = site.publications | where: "path", "/_publications/2024-6-1-TIV-CGT-9-9.md" | first %}
{% assign paper2 = site.publications | where: "path", "/_publications/2024-6-7-Software-Scenario-number-3.md" | first %}
{% assign paper3 = site.publications | where: "path", "/_publications/2024-6-6-Patent-Scenario-number-4.md" | first %}
{% if paper1 %}
  {% include archive-single.html post=paper1 %}
{% endif %}
{% if paper2 %}
  {% include archive-single.html post=paper2 %}
{% endif %}
{% if paper3 %}
  {% include archive-single.html post=paper2 %}
{% endif %}

# Safety Evaluation of Autonomous Driving Algorithm

{% assign paper3 = site.publications | where: "path", "/_publications/paper3.md" | first %}
{% assign paper4 = site.publications | where: "path", "/_publications/paper4.md" | first %}
{% if paper3 %}
  {% include archive-single.html post=paper3 %}
{% endif %}
{% if paper4 %}
  {% include archive-single.html post=paper4 %}
{% endif %}

# Self-Evolve Mechanism of Autonomous Driving Algorithm

{% assign paper5 = site.publications | where: "path", "/_publications/paper5.md" | first %}
{% assign paper6 = site.publications | where: "path", "/_publications/paper6.md" | first %}
{% if paper5 %}
  {% include archive-single.html post=paper5 %}
{% endif %}
{% if paper6 %}
  {% include archive-single.html post=paper6 %}
{% endif %}
