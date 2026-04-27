---
layout: default
title: Home
---

<h1>Huyen Vi</h1>
<p>Về những câu chuyện tôi lượm nhặt quanh tôi</p>

<h2>Writing</h2>
<ul class="post-list">
{% for post in site.posts %}
  <li>
    <div class="post-date">{{ post.date | date: "%b %-d, %Y" }}</div>
    <a class="post-title" href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>