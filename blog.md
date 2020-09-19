---
layout: default
title: The Ramblings of a Thirty Something
---

I've decided to give the whole blogging thing a go. Share some of the things that I've found interesting, things that people may find useful (or at least something I can reference back to as I forget things), and some things I've found out in the wild.

This blog isn't purely computer science, unlike my history in and out of academia.

Strap yourselves in, it will be a tedious ride.

<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
    {% endfor %}
</ul>
