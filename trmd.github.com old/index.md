---
layout: page
title: trmd
<!-- tagline: Supporting tagline -->
---

These are notes, curated from the ones I keep for personal use.

This is inspired by many other projects, such as [Cosma's Notebooks](http://vserver1.cscs.lsa.umich.edu/~crshalizi/notebooks/) and [Boettiger's Lab Notebook](http://www.carlboettiger.info/2012/09/28/Welcome-to-my-lab-notebook.html).

All notes so far:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date: "%Y-%m-%d" }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

[Publications etc…](http://www.gu.se/omuniversitetet/personal/?userId=xjtorm)