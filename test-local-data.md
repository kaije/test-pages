---
layout: default
title: "Test Local Data Retrieval"
---

<p>Trying out local json data retrieval...</p>

{% for quote in site.data.book-quotes %}
<p>
  {{ quote.text }}
  <span>{{ quote.title }} - {{ quote.author }}</span>
</p>
{% endfor %}
