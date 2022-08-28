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
## The Campaign for Revenge
<ul>
  {% for post in site.posts %}
  {% for tag in post.tags %}
  {% if tag == "dungeon quest" %}
    <li>
      <a href="{{ post.url | prepend:site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endif %}
  {% endfor %}
  {% endfor %}  
</ul>

---

# Resources
[Rough Map of Hyperborea](/assets/pdf/mainland_hyperborea_large.pdf)
