# My journal

These are my latest notes

---

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})
*Published on {{ post.date | date: "%d %B %Y" }}*

{{ post.excerpt }}

---
{% endfor %}
