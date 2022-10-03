---
layout: archive
permalink: team-project
title: "team-Project"

author_profile: true
sidebar:
  nav: "docs"
---

{% assign posts = site.categories.team-project %}
{% for post in posts %}
  {% include custom-archive-single.html type=entries_layout %}
{% endfor %}