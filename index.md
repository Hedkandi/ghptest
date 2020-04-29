---
title: sample post
---

<ul>
{% for org_hash in site.data.personas %}
{% assign org = org_hash[1] %}
  <li>
        {% link _site/subpages/nr-one.md %}
      {{ org.name }} - {{ org.interest }}
  </li>
{% endfor %}
</ul>