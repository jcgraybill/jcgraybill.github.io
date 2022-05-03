---
layout: game
permalink: /ship-shape/
game: ship-shape
width: 1366
height: 768
---

This is *ship-shape*. While building [it costs money to be alive](/it-costs-money/) I thought about what kind of game I enjoy playing most - something in the [4X](https://github.com/freeorion/freeorion), [supply-chain](https://github.com/tobspr/shapez.io), [Zachlike](https://www.zachtronics.com), [city-building](https://en.wikipedia.org/wiki/City_Building_(series)) style. I paused work on *it costs money* and decided to try my hand at a space-themed supply-chain game. Space-themed because I didn't want to think about pathfinding. There would be no aliens or enemies - the game would be all about your ability to manage a well-balanced economy. Everything would be done by building structures, and I loved the idea of dozens of teeny little spaceships ferrying cargo all over the place. The distribution of planets and resources is random, so the player may need to choose between putting things close together (which makes the supply chain more efficient, because materials spend less time in transit), or selecting the optimal planets.

I got the basic engine working after a couple of weeks, then spent about a week building a 6-level tutorial and optimizing out some truly embarrassing inefficiencies. The tutorial is playable now - I'm going to playtest this a bit with friends and family, then add a real gameplay mode with objectives, challenges, leaderboards, and a lot more content. So if there's a feature you'd like to see, [open an issue](https://github.com/jcgraybill/ship-shape/issues), I guess.

This is also built with the [ebiten](https://ebiten.org/) 2D game library. All the visuals are created in-engine using Michael Fogleman's [gg](https://github.com/fogleman/gg) graphics library.
