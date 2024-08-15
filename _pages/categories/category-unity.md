---
title: "Unity"
layout: category
permalink: /categories/unity
author_profile: true
taxonomy: Unity
sidebar:
  nav: "categories"
---
{% assign posts = site.categories['unity']%}
{% for post in posts %}
{% include archive-single.html type=page.entries_layout %}
{% endfor %}