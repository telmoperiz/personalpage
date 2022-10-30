---
layout: default
title: Research

publications:
    -title: Titleeee
    coauthors: 
      -E. Pronkina
      -J.C. Escanciano
    journal: Hi
    year: Forthcomming
   
  -title: Titleeee 2222
    coauthors: 
      -E. Pronkina
      -J.C. Escanciano
    journal: Hi
    year: Forthcomming
---

## Publications

<div class="clicker" tabindex="1">Click me</div>
<div class="hiddendiv"></div>

## Working papers

{% for paper in page.publications %}
        <p> paper.title with </p>
        {% for co in paper.coauthors %} co,
        {% endfor %}
        </p>
{% endfor %}

## Work in progress
