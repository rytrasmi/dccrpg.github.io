---
layout: default
---

Please see the [aboutttt](about.md) for further details.

Interesting things are listed below.
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend:site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
