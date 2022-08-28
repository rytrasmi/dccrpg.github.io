---
layout: default
---

Please see the [aboutttt](about.md) for further details.

Characters
Biff 


```
Fenced code blocks are like Standard
Markdown’s regular code blocks, except that
they’re not indented and instead rely on
start and end fence lines to delimit the
code block.
```


Interesting things are listed below.
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend:site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
