---
title: "CV"
layout: archive
permalink: categories/cv
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.CV %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}