---
title: "Home"
---

## The Other Site
Find me [here](https://vmah1ndra.github.io/coldcaches).

## Posts

<details>
  <summary><h5>All Posts</h5></summary>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
</details>

## Tags
<details>
  <summary><h5>All Tags</h5></summary>
{% for tag in site.tags %}
  <details>
  <summary><h3>{{ tag[0] }}</h3></summary>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  </details>
{% endfor %}

</details>
