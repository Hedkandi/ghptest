---
layout: default
title: Staff
---
<h1>testers</h1>

<ul>
  {% for tester in site.testers %}
    <li>
      <h2>{{ tester.name }}</h2>
      <h3>{{ tester.position }}</h3>
      <p>{{ tester.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>