---
---

## Latest Posts

<div>
  {% for post in site.posts %}
    <h2>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </h2>
    {{ post.content }}
  {% endfor %}
</div>
