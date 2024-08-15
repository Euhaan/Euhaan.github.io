---
title: "Algorithm"
layout: category
permalink: /categories/algorithm
author_profile: true
taxonomy: Algorithm
sidebar:
  nav: "categories"
---
{% assign posts = site.categories['algorithm']%}
{% for post in posts %}
{% include archive-single.html type=page.entries_layout %}
{% endfor %}