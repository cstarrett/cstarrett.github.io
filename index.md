---
---

# Latest Posts

{% for post in site.posts %}
## [ {{ post.title }} ]( {{post.url}} )
{{ post.content }}
***
<small>{{ page.date | date: "%-d %B %Y" }}</small>
{% endfor %}
