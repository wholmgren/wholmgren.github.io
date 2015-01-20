---
title: Posts
layout: default
---

## Some articles

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

The list above is automatically generated using Jekyll.
This [page](http://learn.andrewmunsell.com/learn/jekyll-by-example/tutorial) was very useful in getting this set up.
