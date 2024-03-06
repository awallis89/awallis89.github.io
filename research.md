---
layout: page
title: Research
---
This page tells you a **little** bit about me.
## Publications
{% for pub in site.data.publications.proceedings %}
+ {{ pub.authors }}, *"{{ pub.title }}"*, {{ pub.proceeding }}, {{ pub.year }}.
{% endfor %}
