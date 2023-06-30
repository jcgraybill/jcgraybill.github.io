---
layout: default
---

### :wave: 
This is me: [LinkedIn](https://www.linkedin.com/in/jules-graybill/) / [GitHub](https://github.com/jcgraybill) / Mastodon (<a rel="me" href="https://oldbytes.space/@jcgraybill">oldbytes</a> / <a rel="me" href="https://fosstodon.org/@jcgraybill">fosstodon</a>).  Here some things I've done.

### Indie games
I made a few 2D videogames, mostly using the excellent [Ebitengine](https://ebitengine.org/) game library, to scratch my programming itch when I'm not writing software for work. They're all various levels of complete. Here are a few that are playable and even a little fun. Enjoy!
* **❤️ attraction**: A tile-and-grid puzzle game built for the [ebitengine game jam](https://itch.io/jam/ebiten-game-jam). [Play it on itch.io](https://ivlivs.itch.io/attraction).
* **ship-shape**:  Supply chain management... *in space!* [Play it in your browser](/ship-shape/).
* **it costs money to be alive**: A short, simple side scroller. [Play it in your browser](/it-costs-money/).
* **Multi Pong**: A multi-window pong game. Fire up your emulators, blow the dust off that Quadra 650 in the closet, this is playable on Macintosh System 7. Also, you can [try it in your browser](/multi-pong/). 

### Fixing old computers
I'm fixing up a small collection of computers from the 1980s and 1990s, and [writing about the process and what I learn](/vintage-computers/). I'm mostly interested in 8-bit and 16-bit all-in-one home microcomputers from the 1980s (think, Atari, Commodore, Apple...) and UNIX workstations and "beige" Macintoshes from the 1990s.

### OpenSearch
I used to be responsible for [OpenSearch](https://opensearch.org/), an open source fork of [Elasticsearch](https://www.elastic.co/elasticsearch/). I'm no longer involved with OpenSearch, but both it and Elasticsearch are great software.

Try it out! Check your [`vm.max_map_count`](https://opensearch.org/docs/latest/opensearch/install/important-settings/) then...

    curl -O https://opensearch.org/samples/docker-compose.yml
    docker-compose up
    curl -k https://admin:admin@localhost:9200/