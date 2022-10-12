---
title: "About"
layout: posts
permalink: /about/
author_profile: true
sidebar_main: true
---


{% assign posts = site.about %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}