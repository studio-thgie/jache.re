---
title: "Jachère Deployment and Publishing"
author: Adrian Demleitner
date: 2022-04-17
---
# Jachère Deployment and Publishing
The content of la Jachère is managed and collaboratively edited through a [git repository](https://git.sr.ht/~thgie/jache.re), currently residing at [Codeberg](https://codeberg.org).

The deployment is managed by a small script I coded, named [pancake.sh](https://codeberg.org/thgie/pancake.sh). It's a shell script that uses pandoc to render html files from the markdown ones.

I opted for pandoc, since I wanted to keep it simple in terms of tools and toolchain and because some of the content uses citations that are fed from a bibtex file.