---
layout: page
title: Teaching
---
This page tells you a little bit about me.
## Publications


<ul>
    {% for pub in site.data.publications.proceedings %}
        <li>{{ pub.title }}, "{{ pub.author}}" </li>
    {% endfor %}
</ul>