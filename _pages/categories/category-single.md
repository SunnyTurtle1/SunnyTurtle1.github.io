---
title: "Single"
layout: archive
permalink: /categories/single_project/
author_profile: true
sidebar_main: true
---


{% assign posts = site.categories.singlep %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}