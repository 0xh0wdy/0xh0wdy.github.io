---
layout:default
title: 0xh0wdy
---
Howdy! This is a hoard of cheetsheets and ideas I have collected off the interwebs. 

Take a look around:

{% for guide in site.guides %}
- [{{ guide.title }}]({{ guide.url | relative_url }})
{% endfor %}