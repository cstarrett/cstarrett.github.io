---
---

<h1>Latest Posts</h1>

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
{{ post.content }}
<hr/>
<small>{{ post.date | date: "%-d %B %Y" }}</small>
{% endfor %}
