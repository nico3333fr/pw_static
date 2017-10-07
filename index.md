---
title: Woooooooooooozaaaaaaaaaa
description: Plop
unevariable_custom: "pweeeeeeeeeeeeet"
---

# titre de ma page, et là on met du texte

Coucou, tu veux voir mon site statique ?

{{ site.unevariable_custom }}

<ul>
{% for page in site.pages %}
<li><a href="#">{{ page.title }}</a></li>
{% endfor %}
</ul>
