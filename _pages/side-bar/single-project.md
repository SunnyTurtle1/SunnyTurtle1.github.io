---
layout: archive
permalink: single-project
title: "Single-Project"

author_profile: true
sidebar:
  nav: "docs"
---

{% assign posts = site.categories.single-project %}
{% for post in posts %}
  {% include custom-archive-single.html type=entries_layout %}
{% endfor %}