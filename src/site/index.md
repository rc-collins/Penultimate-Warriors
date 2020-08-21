---
title: Penultimate Warriors
subtitle: Radio Warriors watching penultimate episodes
layout: layouts/base.njk
---

## Latest Episodes
<ul class="listing">
{%- for page in collections.episode | reverse -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>

## Feeds

- [XML Feed](http://cast.rocks/hosting/27557/feeds/CAURZ.jpg?e=0df284f)

More Coming Soon

## Connect

Coming Soon

