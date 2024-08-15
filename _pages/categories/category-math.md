---
title: "Math"
layout: category
permalink: /categories/math
author_profile: true
taxonomy: Math
sidebar:
  nav: "categories"
---
{% assign posts = site.categories['math']%}
{% for post in posts %}
{% include archive-single.html type=page.entries_layout %}
{% endfor %}