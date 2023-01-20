---
title: "Jachère Deployment and Publishing"
author: Adrian Demleitner
date: 2022-04-17
---
# Jachère Deployment and Publishing
As of now[^1] this websites lives on a Raspberry Pi 4 in Biel/Bienne, Switzerland, alongside some other stuff. The content of la Jachère is managed and collaboratively edited through a [git repository](https://git.sr.ht/~thgie/jache.re), currently residing at [Codeberg](https://codeberg.org).

The deployment is managed by a small script I coded, named [pancake.sh](https://codeberg.org/thgie/pancake.sh). It's a shell script that uses pandoc to render html files from the markdown ones and pushes them directly into a separate branch of the repository. I opted for pandoc, since I wanted to keep it simple in terms of tools and toolchain and because some of the content uses citations that are fed from a bibtex file.

Last summer[^2] I was playing around with having the server solar-powered. You can read here about the [Solar Setup](notes/solar-setup.md). I ended up, not finding a spot for the panel and thus had suboptimal results. The setup still exists and I will continue next summer with the experiments.

[^1]: 20th January 2023
[^2]: Summer 2022