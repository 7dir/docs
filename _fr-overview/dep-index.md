---
layout: base
title:  'Dependencies'
generated: 'true'
permalink: fr/dep/index.html
udver: '2'
---

# Dependencies

{% include fr-dep-table.html %}

----------

Alphabetical listing

{% assign sorted = site.fr-dep | sort: 'title' %}{% for p in sorted %}
* [{{ p.title }}](): {{ p.shortdef }}{% endfor %}
