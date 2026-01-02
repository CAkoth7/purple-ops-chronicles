---
layout: default
title: Blog
---

# Blog

Reflections and field notes on identity, access, risk, cloud security, and governance written from practice and theory.

---

## Posts

{% for post in site.posts %}
### {{ post.title }}
**{{ post.date | date: "%B %d, %Y" }}{% if post.topic %} · {{ post.topic }}{% endif %}{% if post.reading_time %} · {{ post.reading_time }}{% endif %}**

{{ post.excerpt }}

[Read post →]({{ post.url | relative_url }})

---
{% endfor %}

