---
layout: archive
title: "Publications & Presentations"
permalink: /presentations/
author_profile: true
---

{% include base_path %}

## Publications
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Presentations
{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
