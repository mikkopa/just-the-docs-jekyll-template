---
layout: page
title: Posts
permalink: /posts/
nav_exclude: true
nav_order: 4
search_exclude: true
---

This is a sample page to list and link all posts in _posts folder

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

baseurl: 
{{ site.baseurl }}