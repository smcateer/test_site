---
layout: default
title: Home
---

# Welcome

Intro sentence. Some projs:
<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}
        </li>
    {% endfor %}
</ul>