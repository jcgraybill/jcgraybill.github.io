---
layout: post
title:  "Commodore Amiga 500"
tag: Commodore Amiga
imagedir: amiga
---

Look at this pretty Amiga 500 I found! It came from a seller in Hungary, and it arrived at my house wrapped in Hungarian newspapers for protection. Check out that keyboard layout. 

{% include pic.html n=8579 alt="Amiga 500" %}

Let's take a look inside.

{% include pic.html n=8580 alt="Amiga 500 bottom" %}
{% include pic.html n=8582 alt="Amiga 500 with top of case removed" %}
{% include pic.html n=8583 alt="Amiga 500 with case, keyboard, and disk drive removed" %}

The case gets a good wash, and I'll set it aside to dry while I look around the main board. When summer comes around I'll look into a round of retrobrite to undo some of the yellowing.

***Hey, where is this photo?***

The main board is delightful. Many of the chips have fanciful names, as does the board itself ("Rock Lobster"). Everything is labeled, so it's super clear to follow where things are. It looks like I have 512KB of RAM, and there are little outlines where a person could add four more 128KB RAM modules to upgrade to 1 megabyte.

{% include pic.html n=8584 alt="Amiga 500 main board" %}
{% include pic.html n=8585 alt="Rock Lobster" %}
{% include pic.html n=8587 alt="Denise" %}
{% include pic.html n=8597 alt="Paula" %}
{% include pic.html n=8589 alt="RAM modules" %}

No magic smoke when I plug it in. I have a [DB23-to-VGA adapter from Retrofriends](https://www.retrofriends.com/amiga.htm) - let's try it out.

{% include pic.html n="0001" alt="Amiga attached to power supply" %}
{% include pic.html n=8599 alt="Corrupted Amiga screen image" %}

Uh oh. The picture is really corrupted. Is something on the board corroded or loose? I look everywhere, but it all looks good. The video output area of the board doesn't show anything that looks like corrosion. (Also, these labels are so helpful!) 

{% include pic.html n=8594 alt="Video output section of the main board" %}

Maybe it's an NTSC/PAL issue? I read that you can tell from Jumper ***TODO: which one?***. Looks like this is indeed NTSC.

{% include pic.html n=8598 alt="Fat Angus" %}

It seems unlikely, but maybe the issue is the scandoubler/VGA adapter. I try it with an Amiga 1000 I have on hand, and sure enough, the video is bad too.

{% include pic.html n=8600 alt="Corrupted Amiga screen image" %}

Sure enough, I try composite output, and the image is much clearer.

{% include pic.html n=8602 alt="Less corrupted Amiga screen image" %}

***Try the other adapters***