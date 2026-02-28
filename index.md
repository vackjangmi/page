---
layout: default
title: Home
---

# 👋 안녕하세요

여기는 내 GitHub Pages 블로그입니다.

## 최신 글
<ul>
  {% for post in site.posts limit: 10 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small> — {{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>