---
layout: default
title: Posts
---

## Viewing All Posts

<ul>
    {% for post in site.posts %}
        <li>{{ post.date | date_to_string }} &raquo; 
        <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
