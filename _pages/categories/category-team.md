---
title: "Team"
layout: archive
permalink: /categories/team_project/
author_profile: true
sidebar_main: true
---


{% assign posts = site.categories.team_project %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}