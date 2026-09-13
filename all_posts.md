---
layout: allposts
title: All posts
landing-title: 'All posts'
nav-menu: true
description: null
image: null
author: null
show_tile: false
---

<h1>All posts</h1>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
