---
layout: default
title: Welcome to The Metrics Investor
---

# Welcome to The Metrics Investor
Discover data-driven investment strategies with The Metrics Investor. Follow our journey as we use a custom stock screener to build a high-growth portfolio with consistent monthly updates and actionable insights.

## Latest Posts
<ul>
  {% for post in site.posts %}
    {% if post.date <= site.time %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a> <br>
        <small>Published on {{ post.date | date: "%B %d, %Y" }}</small>
      </li>
    {% endif %}
  {% endfor %}
</ul>