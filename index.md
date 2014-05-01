---
layout: page
title: Concept Notes
<!-- tagline: Supporting tagline -->
---

These are notes, curated from the ones I keep for my research. Mainly I work on a doctoral dissertation in public law. But many other topics can be found here.

This is inspired by many other projects, but most notably [Cosma's Notebooks](http://vserver1.cscs.lsa.umich.edu/~crshalizi/notebooks/) and [Boettiger's Lab Notebook](http://www.carlboettiger.info/2012/09/28/Welcome-to-my-lab-notebook.html).

These are all notes so far:

<ul class="posts">
  {% for post in site.posts %}
    <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }} </a><span>{{ post.date | date: "%Y-%m-%d" }}</span> </li>
  {% endfor %}
</ul>

