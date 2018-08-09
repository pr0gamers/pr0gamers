---
layout: page
show_meta: false
title: "Existem algumas regras!"
subheadline: "Pra não ter confusão"
header:
   image_fullwidth: "header_regras.png"
permalink: "/regras/"
---





<ul>
    {% for post in site.categories.regras %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
