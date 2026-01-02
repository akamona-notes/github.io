# AKA Mona

Late-diagnosed autistic. No brand to build, nothing to sell. I am just someone working in an office somewhere, putting thoughts together to make sense of the systems we live in, and trying to connect with others. 
These are my latest notes

---

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})
*Published on {{ post.date | date: "%d %B %Y" }}*

---
{% endfor %}
