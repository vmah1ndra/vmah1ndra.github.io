---
title: "Home"
---

## The Other Site
Find me [here](https://vmah1ndra.github.io/coldcaches).

## Posts

<details><summary><h3>All Posts</h3></summary>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
</details>

## Tags
<details><summary><h3>All Tags ({{ site.tags | size }})</h3></summary>
{% for tag in site.tags %}
  <details><summary><h5>{{ tag[0] }} ({{ tag[1] | size }})</h5></summary>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  </details>
{% endfor %}

</details>
