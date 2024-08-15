---
title: "C"
layout: category
permalink: /categories/c
author_profile: true
taxonomy: c
sidebar:
  nav: "categories"
---
{% assign posts = site.categories['c']%}
{% for post in posts %}
{% include archive-single.html type=page.entries_layout %}
{% endfor %}