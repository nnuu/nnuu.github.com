---
layout: page
title: Kingz
---
{% include JB/setup %}

你正在访问凉金泽的个人网站。

#### 最近发布的文章

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
