---
layout: post
title:  "Getting online, part 1"
tag: Beige Macintoshes
imagedir: beigemacs
---
The two challenges to getting the 1990s macintoshes online are:

1. Web browsers from this era don't implement modern web standards - specifically SSL - and so most websites won't even allow connections from them. It looks like this can be worked around by using a proxy server: I'm going to try [the WebOne proxy](https://github.com/atauenis/webone) for this.
2. Only one of the computers - a Power Macintosh G3 from 1997 - even has an [RJ45 Ethernet port](https://en.wikipedia.org/wiki/Modular_connector#8P8C). This is what I'm tackling in this blog post.

A couple of them have proprietary [AAUI-15 ports](https://en.wikipedia.org/wiki/Apple_Attachment_Unit_Interface), which seems to be easy enough to work around, with these [Farallon EtherMac 10Base-T Ethernet AAUI transceivers](https://apple.fandom.com/wiki/EtherMac), which I found at [Tech by Androda](https://androda.work/product/farallon-pn512b-aaui-10-baset-ethernet-transceiver/). 

{% include pic.html n=8644 alt="Farallon EtherMac 10Base-T Ethernet AAUI adapter" %}

The oldest one, a [Centris 610](https://lowendmac.com/1993/centris-610/), doesn't even have an AAUI port, and it's not easy to find an Ethernet expansion card that's compatible with the Centris's [Quadra Processor Direct (PDS) slot](https://en.wikipedia.org/wiki/Processor_Direct_Slot#Quadra_PDS_(Motorola_68040)). In fact, I don't even see any compatible cards on [this list of classic Macintosh expansion cards](https://wiki.preterhuman.net/List_of_expansion_cards_for_Macintosh). What I *was* able to find were a lot of [NuBus](https://en.wikipedia.org/wiki/NuBus)-compatible Ethernet cards on eBay, as well as this PDS-to-NuBus adapter (M1402LL/A) made specifically for the Centris 610. Let's try them out!

{% include pic.html n=8568 alt="Macintosh Centris 610 NuBus Adapter Card package, NuBus Ethernet card, Macintosh Centris 610" %}
