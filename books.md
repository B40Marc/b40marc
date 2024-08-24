---
layout: page
title: Books
categories: books
---

This is where I share books I am reading



{% for books in site.books %}
  <h2>{{ books.name }} - {{ books.author }}</h2>
  <p>{{ books.content | markdownify }}</p>
{% endfor %}
