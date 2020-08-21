---
title: Penultimate Warriors
subtitle: Radio Warriors watching penultimate episodes
layout: layouts/base.njk
---

## Latest Episodes

<ul class="listing">
{%- for page in collections.episode | reverse -%}
  {% if loop.index0 < 5 %}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
  {% endif %}
{%- endfor -%}
  <li>
    <a href="/episodes">See More</a>
  </li>
</ul>


## Feeds

- [XML Feed](http://cast.rocks/hosting/27557/feeds/IIJH4.xml)

More Coming Soon

## Connect

[penultimatewarriors@gmail.com](mailto:penultimatewarriors@gmail.com)

