---
layout: default
---

This is the campaign log for an ongoing game of Hyperborea 3E run in Toronto. The campaign is open and you may [join the adventure](join.md)!

---

# Adventurers
## Biff
Biff is a Common magician.

## Jill
Jill is a Pict fighter who seeks out danger.
> I say we slay the lot of them!

---

# Places
## Khromarium
This is the big city.

## Some place
It is dark and stormy here. A witch-queen rules over it.

---

# Chronology
{% for category in site.categories %}
## {{ category[0] | capitalize }}
{% for post in category[1] %}
### <a href="{{ post.url | prepend:site.baseurl}}">{{ post.title }}</a>
{{ post.inwhich }}
{% endfor %}
{% endfor %}

---

# Resources
[Rough Map of Hyperborea](/assets/pdf/mainland_hyperborea_large.pdf)
