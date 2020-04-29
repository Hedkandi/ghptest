---
title: sample post
---

<ul>
{% for post in site.posts %}
  <li>
      {{ post.name }} - {{ post.interest }}
  </li>
{% endfor %}
</ul>