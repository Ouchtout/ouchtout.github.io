---
layout: page
title: "Events"
permalink: /events/
---

{% for post in site.events %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
