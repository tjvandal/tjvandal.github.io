---
layout: default
title: Blog
---
<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{post.date | date_to_string}} - {{post.title}}</a></h3>
    </li>
  {% endfor %}
</ul>

