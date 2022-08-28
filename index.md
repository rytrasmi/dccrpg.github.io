---
layout: default
---

Please see the [aboutttt](about.md) for further details.

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
  ##{{ category[0] }}
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

---

# Resources
[Rough Map of Hyperborea](/assets/pdf/mainland_hyperborea_large.pdf)
