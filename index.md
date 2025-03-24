---
layout: default
title: Rating Waterloo Donkeys.... since 2025
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .footer {
    display: none;
  }
</style>
