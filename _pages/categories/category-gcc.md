---
title: "GCC"
layout: category
permalink: /categories/gcc
author_profile: true
taxonomy: GCC
sidebar:
  nav: "categories"
---
{% assign posts = site.categories['gcc']%}
{% for post in posts %}
{% include archive-single.html type=page.entries_layout %}
{% endfor %}