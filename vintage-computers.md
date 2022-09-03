---
layout: default
permalink: /vintage-computers/
---

### restoring vintage computers
![Vintage computer collection](/assets/images/pvlcm.jpg) 

One of my favorite places in Seattle was the [Living Computer Museum + Labs](https://www.livingcomputers.org/), which is indefinitely - likely permanently - closed. Perhaps some civic-minded billionaire will reopen it to the public one day. In the meantime, I made a list of the computers that were most interesting to me - primarily 8-bit and 16-bit home computers from the 1980s, plus a few pizza-box UNIX workstations and Macintoshes from the 1990s - then set about getting ahold of as many as I could. I've been cleaning them up, restoring them, (occasionally) retrobriting them back toward their original color, and generally getting them into condition where they can be displayed and used. I will be documenting the process and what I learn here. 

{% for tag in site.tags %}
<h3>{{ tag[0] }}</h3>
<ul>
{% for post in tag[1] %}
<li><a href="{{ post.url }}">{{ post.title }}</a> {{ post.excerpt }}</li>
{% endfor %}
</ul>
{% endfor %}