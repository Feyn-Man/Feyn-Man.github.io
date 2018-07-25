---
title: "Reading"
layout: page
image:
  path: /images/reading-1600x600.jpeg
  thumbnail: /images/reading-400x200.jpeg
  caption: "Photo by Mikes Photos from [Pexels](https://www.pexels.com)"
permalink: /interests/reading/
read: 1
---
{% assign entries = site.reading %}


{%- for post in entries -%}
  {% include entry.html %}
{%- endfor -%}
