---
layout: default
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | absolute_url }}">{{ post.title }}</a> – {{ page.date | date: "%Y-%m-%d" }}
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
