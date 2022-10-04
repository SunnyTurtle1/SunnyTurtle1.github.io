---
title: "Single"
layout: archive
permalink: categories/single-project
author_profile: true
sidebar_main: true
---


{% assign posts = site.categories.single-project %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}