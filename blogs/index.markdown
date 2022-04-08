---
layout: post
title: Blogs
permalink: /blogs/
---
## How to
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
