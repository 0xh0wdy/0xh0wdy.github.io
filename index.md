---
layout:default
title: 0xh0wdy
---

Take a look around, save what you want. I hope it helps you as much as it has helped me.

{% for guide in site.guides %}
- [{{ guide.title }}]({{ guide.url | relative_url }})
{% endfor %}