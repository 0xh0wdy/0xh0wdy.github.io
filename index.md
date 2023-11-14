---
layout:default
title: 0xh0wdy
---
Welcome to my website! This is place where I keep study guides and cheat sheets. I hope this helps you as much as it helps me.

Here are some topics:

{% for guide in site.guides %}
- [{{ guide.title }}]({{ guide.url | relative_url }})
{% endfor %}