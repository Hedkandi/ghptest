---
layout: post
title: NR ONE!!
customVar: nr-one
---

<ul>
{% for org_hash in site.data.personas %}
{% assign org = org_hash.{{ post.customVar }} %}
  <li>
    <a href="https://github.com/{{ org.username }}">
      {{ org.name }}
    </a>
    ({{ org.members | size }} members)
  </li>
{% endfor %}
</ul>