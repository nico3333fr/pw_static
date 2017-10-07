---
title: Woooooooooooozaaaaaaaaaa
description: Plop
unevariable_custom: "pweeeeeeeeeeeeet"
---

# titre de ma page, et là on met du texte

Coucou, tu veux voir mon site statique ?

{{ site.unevariable_custom }}

<ul>
{% for page in site.html_pages %}
<li><a href="{{ site.url }}{{ page.url }}">{{ page.title }}</a></li>
{% endfor %}
</ul>
