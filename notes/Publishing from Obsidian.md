# Publishing from Obsidian

### pandoc
Just install this one and forget about it. Installation guide can be found here: https://pandoc.org/installing.html.

## Exporting from Obsidian…

### …to documents
First, you need to export a Zotero collection or your whole library (not recommended if you have many items).

- Right-click the collection you want to export and chose **Export Collection…**

![](assets/Screenshot%202022-08-19%20at%2020.28.33.png)

The settings you should have ticked are:

- Export Notes (enables you to import your notes and annotation into Obsidian)
- Use Journal Abbreviation (can't remember why, just do it)
- Keep updates (when you add another source to that collection in Zotero it will automatically make a new export)

Use the path to the Zotero BibTeX export file and put it into *Citation database path*. You're free in using whatever you want for *Literature note folder*. That is just the place where the notes end up that you import from Zotero.

As a last step, go into the **pandoc** plugin settings and put the following preferences:

![](assets/Screenshot%202022-08-19%20at%2020.31.41.png)

- Export files from HTML or markdown: **Markdown**
- Export folder: **Whatever you want**, I like mine in the same place all the time
- Pandoc path: **Use their guide in the little note to find this value**, you can use mine (`/usr/local/bin/pandoc`) on macOS
- Extra Pandoc arguments: **This is important**

```sh
--bibliography=/Users/adrian/path/to/Export.bib --citeproc --csl=/Users/adrian/path/to/Citation-Style.csl
```

If you don't know what a citation style is yet, just leave out the `--csl=/Users/adrian/path/to/Citation-Style.csl` part. This little piece of information will let pandoc know, that you used references in your text, and tries to replace them accordingly during export.

### …to websites
#todo, but I personally use [pancake.sh](https://codeberg.org/thgie/pancake.sh) for that. It's a bunch of scripts I wrote myself to generate a website from an Obsidian vault.