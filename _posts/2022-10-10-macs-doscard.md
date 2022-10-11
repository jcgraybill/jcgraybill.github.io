---
layout: post
title:  "The Apple DOS compatibility card"
tag: Beige Macintoshes
---

The late "beige macintosh" era from 1991-1998 produced a mind-boggling number of products - computers of different shapes, sizes, and capabilities; accompanied by a wild set of operating systems, software, accessories, and peripherals. Most of these came and went within a year or two after launch. Apple's corporate history is so easy to see in [Wikipedia's visual timeline of Macintosh models](https://en.wikipedia.org/wiki/List_of_Mac_models#Timeline). Before 1991, there were basically two products, each getting incremental improvements: the all-in-one Macs that looked like the original 128K macintosh, and the Macintosh II, that looked like a shoebox. After the launch of the iMac in 1998, they quickly reduce to the five product lines that exist to this day: the iMac, a consumer and pro desktop, and a consumer and pro laptop. In between those eras, holy moly! Quadras! Powerbooks! Newtons! Workgroup Servers! Performas! The [Molar Mac](https://happymacs.wordpress.com/2016/12/06/the-power-mac-g3-all-in-one-molar-mac/)! The [Twentieth Anniversary Macintosh](https://en.wikipedia.org/wiki/Twentieth_Anniversary_Macintosh)!

[![Timeline of Macintosh models](/assets/images/beigemacs/t/macintosh-timeline-small.png)](https://en.wikipedia.org/wiki/List_of_Mac_models#Timeline)

It felt like Apple was floundering during this era, dumping tons of resources into R&D in a vain attempt to land on some new product that would connect with customers. All while the things that had originally differentiated Macintoshes became less and less relevant in the face of Pentium CPUs, Windows 3.1 and 95, PC sound and graphics cards, and the internet.

As a collector, this era is a *gold mine* of weird, interesting computer products, many of which were too expensive at the time to be within reach.

I learned C on a [Centris 610](https://en.wikipedia.org/wiki/Macintosh_Quadra_610) in [my college](https://www.grinnell.edu/)'s computer lab, so these pizza-box Macs have a special place in my heart. Plus they stack nicely in my office, so a modest-sized collection doesn't take up much space. I'm using a restored Centris 610 right now to participate in a [68K Macintosh programming study group](https://tinkerdifferent.com/threads/idea-macintosh-68k-programming-study-group.1681/) at [Tinker Different](https://tinkerdifferent.com/). Try out my first game "[Multi Pong](https://github.com/jcgraybill/multipong/releases/tag/1.0-beta.2)" in an emulator, or on your own vintage Macintosh! I also have a Quadra 610 I'm trying to bring back from the dead, to run Apple's short-lived UNIX-based operating system [A/UX](https://en.wikipedia.org/wiki/A/UX) on.

[![Macintosh Centris 610](/assets/images/beigemacs/t/IMG_7820.jpeg)](/assets/images/beigemacs/IMG_7820.jpeg)

One product I desperately wanted to try out was Apple's [DOS Compatibility Card](https://www.edibleapple.com/2009/12/09/blast-from-the-past-a-look-back-at-apples-dos-compatibility-cards/). These days, if you want to run multiple operating systems on a single computer, you can either dual-boot between the two of them or do some sort of virtualization. Back in 1994, a real impediment to buying a Macintosh was the fact that some software that people considered essential was only available for DOS or Windows. Since Macs were built around an entirely different processor architecture than PCs, dual-booting and most types of virtualization weren't an option. The first [software-based emulator for Macintoshes](https://en.wikipedia.org/wiki/Windows_Virtual_PC#Virtual_PC_by_Connectix) wasn't even released until 1997, and it was unusably slow. Apple's solution was, hey man, what if you just cram an entire Intel-486-based PC onto an expansion card and have people install that in their Macs? They'll literally run two separate computers inside the same case. Problem solved!

And I found one of these cards - check it out! The 66-MHz 486DX is in the lower left, under the black metal heat sink. On the far left is 16MB of RAM - this was optional, as the card would use the Mac's memory if you didn't provide your own dedicated RAM. The NuBus slot that connects to the Mac's logic board is on the right side, and you can see near the top the black the composite video/joystick port. 

[![Apple DOS Compatibility card](/assets/images/beigemacs/t/IMG_8016.jpeg)](/assets/images/beigemacs/IMG_8016.jpeg)

I planned to install this into a [Power Macintosh 6100](https://en.wikipedia.org/wiki/Power_Macintosh_6100) - what I was able to find was a Performa 6116CD, which is the same hardware but would have come bundled with different software when it was originally sold. The plastic is pretty yellowed and has some stains, but the capacitors look good, and the CD & floppy drive both work. The battery was intact but dead. This model requires battery power to start the video hardware for some reason, so I put in a new battery. The video port is [HDI-45](https://en.wikipedia.org/wiki/HDI-45_connector), an incredibly short-lived port that's so proprietary you need a special adapter to connect it to one of Apple's own *already proprietary* monitor cables. Fortunately, I found an adapter.

[![Performa 6116CD](/assets/images/beigemacs/t/IMG_8017.jpeg)](/assets/images/beigemacs/IMG_8017.jpeg) [![Performa 6116CD label](/assets/images/beigemacs/t/IMG_8018.jpeg)](/assets/images/beigemacs/IMG_8018.jpeg) [![Inside of Performa 6116CD](/assets/images/beigemacs/t/IMG_8019.jpeg)](/assets/images/beigemacs/IMG_8019.jpeg) [![HDI-45 adapter](/assets/images/beigemacs/t/IMG_8020.jpeg)](/assets/images/beigemacs/IMG_8020.jpeg)

With everything plugged in and cleaned up, it boots! Now we just wait *fifty minutes* for Mac OS 9.1 (the latest that will run on this hardware) to install from CD.

[![Performa 6116CD booting to Mac OS 9.1](/assets/images/beigemacs/t/IMG_8021.jpeg)](/assets/images/beigemacs/IMG_8021.jpeg) [![Mac OS 9.1 installer](/assets/images/beigemacs/t/IMG_8022.jpeg)](/assets/images/beigemacs/IMG_8022.jpeg)

Installing the card demands serious legerdemain to work around the existing internal cables and ribbons. Once installed, it looks pretty dull - the plain metallic backside of the card is all that's visible. Video goes out through a passthrough cable, requiring another easy-to-lose adapter. [This LGR YouTube video](https://www.youtube.com/watch?v=9UclHrIIaYA) was helpful in figuring this one out.

[![Installed card](/assets/images/beigemacs/t/IMG_8023.jpeg)](/assets/images/beigemacs/IMG_8023.jpeg) [![Mess of cables](/assets/images/beigemacs/t/IMG_8024.jpeg)](/assets/images/beigemacs/IMG_8024.jpeg)

And it worked! After adding some software enablers to Mac OS, I can command-enter to switch back and forth between Mac OS and DOS, and install Windows 3.1 to the DOS drive. It works like a charm. The DOS and Windows environments have all the drivers they need to work with the Mac hardware, and there are some neat tricks like a shared clipboard and the fact that the DOS drive is a disk image file in Mac OS - which means you can back up, restore, or entirely change out the DOS C: and D: drives without rebooting the Mac.

[![Heresy!](/assets/images/beigemacs/t/IMG_8066.jpeg)](/assets/images/beigemacs/IMG_8066.jpeg)

Delightful, technically novel, surprisingly easy to use, powerful, overpriced, short-lived, poor-selling, unnecessary. Apple Computers in the 1990s.