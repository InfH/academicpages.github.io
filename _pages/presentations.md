---
layout: archive
title: "Publications & Presentations"
permalink: /presentations/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
