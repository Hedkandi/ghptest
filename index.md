---
title: sample post
---

<ul>
{% for org_hash in site.data.personas %}
{% assign org = org_hash[1] %}
  <li>
      {{ org.name }} - {{ org.interest }}
  </li>
{% endfor %}
</ul>