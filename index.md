---
layout:default
title: 0xh0wdy
---
Welcome to my website! This is place where I keep study guides and cheat sheets. I hope yjey help you as much as they helped me.

Here are some topics:

{% for guide in site.guides %}
- [{{ guide.title }}]({{ guide.url | relative_url }})
{% endfor %}