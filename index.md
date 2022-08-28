---
layout: default
---

Please see the [aboutttt](about.md) for further details.

# Characters
## Biff
Biff is a Common fighter who has yet to slay a foe.

## Jill
Jill is a Pict magician who likes casting spells.

> Fenced code blocks are like Standard Markdown’s regular code blocks, except that they’re not indented and instead rely on start and end fence lines to delimit the code block.


# Locations
## Khromarium
This is a city

## Some place
It is dark and stormy here.

```
Fenced code blocks are like Standard
Markdown’s regular code blocks, except that
they’re not indented and instead rely on
start and end fence lines to delimit the
code block.
```


# Chronology
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend:site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
