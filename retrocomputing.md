---
layout: default
permalink: /retrocomputing/
---

### retrocomputing

One of my favorite places in Seattle was the [Living Computer Museum + Labs](https://www.livingcomputers.org/), which is indefinitely - likely permanently - closed. Perhaps some civic-minded billionaire will reopen it one day. In the meantime, I've cobbled together a modest collection of my favorite retro computers, primarily 8-bit and 16-bit home computers from the 1980s, plus UNIX workstations and Macintoshes from the 1990s. I've done restorations and upgrades that are within my capabilities as needed. Stay a while and listen.

{% for tag in site.tags %}
<h4>{{ tag[0] }}</h4>
<ul>
{% for post in tag[1] %}
<li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
{% endfor %}