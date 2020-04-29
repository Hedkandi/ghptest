---
title: sample post
author: nrone.json
---

{% assign tester = site.data.testers[page.author] %}
<a rel="author"
  href="https://twitter.com/{{ tester.name }}"
  title="{{ author.name }}">
    {{ author.name }}
</a>