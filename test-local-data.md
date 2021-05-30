---
layout: default
title: "Test Local Data Retrieval"
---

<p>Trying out local json data retrieval...</p>

{% for quote in site.data.book-quotes %}
<figure>
  <blockquote>
    {{ quote.text }}
    <span>{{ quote.title }} - {{ quote.author }}</span>
  </blockquote>
  <figcaption>
    {{ quote.author }}, <cite>{{ quote.title }}</cite>
  </figcaption>
</figure>
{% endfor %}
