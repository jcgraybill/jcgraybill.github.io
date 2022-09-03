---
layout: game
permalink: /it-costs-money/
game: it-costs-money
width: 1024
height: 512
youtube: https://www.youtube.com/embed/phaNrbvxWAY
---

### it costs money to be alive
This is *it costs money to be alive*. While learning [Go](https://golang.org/), I was looking for some variety from the [usual](https://adventofcode.com/) [exercises](https://amazon.com/dp/1680501224) I use to learn a new language. I decided to make a small game, looked around for a moderately-priced tileset that inspired me, and used the [ebitengine](https://ebiten.org/) 2D game library. All the levels are .csv files and live-reload in the game engine, so it's easy to build new levels using (of all things) Microsoft Excel.

There's not much to the game. I didn't want to build something about guns and fighting. You run to the end of the level, picking up as many coins as you can. Go fast: every second or so you lose a coin you've already picked up because, you know, it costs money to be alive. It's a metaphor for the rat race or something.

One playable level is in the game, several more are *in my head*. Find the [source code](https://github.com/jcgraybill/it-costs-money) on GitHub.