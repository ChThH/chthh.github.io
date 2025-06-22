---
layout: home
title: About me
---

# Welcome to my site!

I’m Christopher, a data analyst who also writes reflections.

Feel free to explore my blog and projects.

---

## Latest Posts

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}

---

## Contact

You can reach me at [your-email@example.com].

