---
title: "Reading"
layout: default
image:
  path: /images/reading-1600x600.jpeg
  thumbnail: /images/reading-400x200.jpeg
  caption: "Photo by Mikes Photos from [Pexels](https://www.pexels.com)"
permalink: /interests/reading/
read: 1
---
{% for item in site.reading %}
{% if section.read == page.read %}
{{ section.output }}
{% endif %}
{% endfor %}
