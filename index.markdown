---
layout: default
---

### :wave: 
This is me: [LinkedIn](https://www.linkedin.com/in/jules-graybill/) / [GitHub](https://github.com/jcgraybill) / Mastodon: <a rel="me" href="https://fosstodon.org/@jcgraybill">fosstodon.org</a> / <a rel="me" href="https://oldbytes.space/@jcgraybill">oldbytes.space</a>.  Some things I've done:

### Restoring vintage computers
I'm restoring a small collection of computers from the 1980s and 1990s, and [documenting the process and what I learn](/vintage-computers/). 

### Open source games
I've been writing 2D videogames, mostly using the excellent [Ebitengine](https://ebitengine.org/) game library, to scratch my programming itch when I'm not writing software at work. They're all various levels of complete. Here are a few that are playable and even a little fun. Enjoy!
* **❤️ attraction**: A tile-and-grid puzzle game built for the [ebitengine game jam](https://itch.io/jam/ebiten-game-jam). [Play it on itch.io](https://ivlivs.itch.io/attraction).
* **ship-shape**:  Supply chain management... *in space!* [Play it in your browser](/ship-shape/).
* **it costs money to be alive**: A short, simple side scroller. [Play it in your browser](/it-costs-money/).
* **Multi Pong**: Fire up your emulators, this is playable on Macintosh System 7. Built as part of the [68k programming study group](https://tinkerdifferent.com/threads/idea-macintosh-68k-programming-study-group.1681/) on [Tinker Different](https://tinkerdifferent.com/). [Get it here](https://github.com/jcgraybill/multipong/releases).

### OpenSearch
I was once in charge of [OpenSearch](https://opensearch.org/), an open source fork of [Elasticsearch](https://www.elastic.co/elasticsearch/). I'm no longer involved with OpenSearch, but both it and Elasticsearch are great software.

Try it out! Check your [`vm.max_map_count`](https://opensearch.org/docs/latest/opensearch/install/important-settings/) then...

    curl -O https://opensearch.org/samples/docker-compose.yml
    docker-compose up
    curl -k https://admin:admin@localhost:9200/
