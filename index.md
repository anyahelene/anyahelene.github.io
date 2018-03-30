---
layout: default
tagline: <em><a href="/">/</a></em>
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | absolute_url }}">{{ post.title }}</a> – {{ post.date | date: "%Y-%m-%d" }}
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
