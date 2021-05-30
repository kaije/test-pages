---
layout: default
title: "Test Local Data Retrieval"
---
# Test Local Data Retrieval

{% for quote in site.data.book-quotes %}
<figure>
  <p>
    {% for line in quote.text %}
      {{ line }}
      <br>
    {% endfor %}
  </p>
  <figcaption>
    <cite>{{ quote.title }}</cite> by {{ quote.author }}
  </figcaption>
</figure>
<hr>
{% endfor %}
