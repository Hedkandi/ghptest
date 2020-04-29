---
layout: default
title: Staff
---
<h1>testers</h1>

<ul>
  {% for tester_hash in site.data.testers %}
  {% assign tester = tester_hash[1] %}
    <li>
      <h2>{{ tester.name }}</h2>
      <h3>{{ tester.position }}</h3>
      <p>{{ tester.content }}</p>
    </li>
  {% endfor %}
</ul>