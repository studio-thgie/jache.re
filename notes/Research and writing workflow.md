---
title: "Research and writing workflow"
author: "Adrian Demleitner"
tags:
	- research basics
	- writing basics
---
# Research and writing workflow
*This is a work in progress and might be heavily expanded upon in the near or far future.*

**Table of Content**

- [Introduction](#introduction)
- [Overview: Tool and workflow outline](#over-tool-and-workflow-outline)
- [Basic Setup Tools](#basic-setup-tools)
- [Basic Setup Plugins](#basic-setup-plugins)
- [Explanations of the setup](#explanations-of-the-setup)
- [Import notes and annotations…](#import-notes-and-annotations)
	- […from Zotero](#from-zotero)
	- […from websites](#from-websites)
- [Writing](#writing)
- [Related](#related)

I'm pretty happy with my research and writing setup. It works well enough for me to make recommendations to people. Here, I try to write-up my current workflow and the tools involved.

## Introduction
In research, you always collect, manage, and consume material such as scientific papers, other textual material, images and videos etc. Guided by your inquiry, research question or project, you produce something new out of the collected and worked on material and your own thoughts. In the last stage, you want to hand your new thing over to other people.

I have four main tools in my setup:

- [Obsidian](https://obsidian.md/)
- [Zotero](https://www.zotero.org/)
- [hypothes.is](https://hypothes.is/)
- [Tropy](https://www.tropy.org/)

All of them are free. Zotero and Obsidian offer paid services that you generally don't need, except if you want to make your life easier or become a power user. Zotero, Tropy and hypothes.is are even open-source. Something I always like. Open-source software enables data sustainability.

In Obsidian you'll work with markdown files, which are basically just slightly structured plain text files that you have on your own computer. Zotero works with a database that you can sync to an online service. It has fantastic export abilities. hypothes.is is also a service, and has a vibrant community, as well as some great export functionalities.  Tropy is an application to collect and manage images that you need for your research.

There is only simple rule in place, that pretty much defines what tools I'm using: [Own your data!](notes/Own%20your%20data!.md)

## Overview: Tool and workflow outline
| Tool              | Actions                                            |
| ----------------- | -------------------------------------------------- |
| **Collecting**    |                                                    |
| *Firefox*         | Browse the web, access content                     |
| *Zotero*          | Collect and manage bookmarks, references, and PDFs |
| *Tropy*           | Collecting and manage images                       |
| **Consuming**     |                                                    |
| Zotero            | Read, annotate and highlight PDFs                  |
| hypothes.is       | Read, annotate and highlighte texts online         |
| **Writing**       |                                                    |
| Obsidian          | Making notes, connections and write                |
| Zotero            | Providing references and raw reading notes         |
| **Publishing**    |                                                    |
| Obsidian + pandoc | Export from Obsidian to documents                  |
| pancake.sh        | Transform a Obsidian Vault into a website          |

## Basic Setup Tools
*Please use Firefox as your browser… You could use any other browser, but why would you want that?*

- Download and install [Firefox](https://www.mozilla.org/en-US/firefox/new/)
- Download and install [Zotero](https://www.zotero.org) 
- Download and install [Obsidian](https://obsidian.md) 
- Open an account at [hypothes.is](https://web.hypothes.is/)

## Basic Setup Plugins
Plugins enable the communication between Firefox, Obsidian and Zotero.

- Firefox
	- [Zotero Connector](https://www.zotero.org/download/) for Firefox. This enables you to safe all kinds of material from the web, from websites, to papers, to videos as a reference in Zotero. I said reference, but we'll talk about that later.
	- Install the [hypothesis bookmarklet](https://web.hypothes.is/help/installing-the-bookmarklet/)
- Obsidian
	- [Zotero Integration](https://github.com/mgmeyers/obsidian-zotero-integration): Import and use references that you collected in Zotero as well as automatically import your reading notes from Zotero.
	- [Hypothes.is](https://github.com/weichenw/obsidian-hypothesis-plugin): Import your annotations from hypothes.is
	- [pandoc](https://github.com/OliverBalfour/obsidian-pandoc): This is a plugin that makes Obsidian able to talk to pandoc. Export your writings, including well formatted references, into documents of your choice, including PDFs or Word files
	- [Footnotes](https://github.com/MichaBrugger/obsidian-footnotes): Since footnotes in Markdown are a bit tedious to produce, this plugin comes handy, but it messes up a bit.
	- [Tidy Footnotes](https://github.com/charliecm/obsidian-tidy-footnotes): Cleans the footnote mess…
- Zotero
	- Install the [ZotFile](http://zotfile.com/) plugin installed. It's helps to work with the PDF files in such basic things as automatic renaming, so all your files have the same naming convention (yes, that is important, you don't want to have a mess, do you?).
	- Also install the [Better BibTeX](https://retorque.re/zotero-better-bibtex/) plugin. This thingy enables Zotero to produce proper citation keys and make wonderful exports of your collections. That will be important later.

## Explanations of the setup
### Firefox
With the Zotero and hypothes.is plugins in place, you can easily start to collect websites, references and PDFs or annotate online articles.

### Zotero
In Zotero you collect references to things you want to keep, read, work through, cite in your texts, etc. The references can either just point to another place, like a bookmark, but they can also contain attachments. These attachments are usually either a locally saved snapshot of a website, in case it ever goes offline, but you still need the content, or in most cases, a PDF of the text you want to read.

When you do academic writing, it is best practice to reference your sources that you built upon. As is typical with an academic process, this can be tedious and painful. Zotero tries to take the pain out of it. You can have a folder with all your sources, for example, and with a few clicks have a proper formatted list of sources that you can paste into your document.

Zotero is also a wonderful tool to read and annotate PDFs. Have a look at the [PDF Reader and Note Editor](https://www.zotero.org/support/pdf_reader) guide. It syncs with mobile, so you could also read on your phone or tablet. I usually make all reading notes in Zotero, even if I don't have a PDF. I simply add the book as a reference (for example via [worldcat.org](https://www.worldcat.org/)) and attach a reading note to it.

### Obsidian
This is where the magic happens. Alternatively, you could have a look at [Zettlr](https://www.zettlr.com/). Compared to Obsidian, it is completely open-source, and the developer is super sympathetic. But it's too sluggish for me and the plugin ecosystem is practically non-existent, making it hard to extend. Obsidian is basically a text-editor with superpowers. One of the basic ideas is, that you can write in something and easily link to another file, over time building up a strong knowledge network.

The goal is actually to get as much material as possible into Obsidian. This is where you spent most of your productive time. Going over your notes and annotations, your resources, piecing them all together and at last, come up with your own material. How exactly you work in Obsidian is up to you and a whole other rabbit whole I fell in several times…

## Import notes and annotations…
### …from Zotero
There is a good explanation under [Notetaking for Historians - Zotero Integration Setup](https://publish.obsidian.md/history-notes/01+Notetaking+for+Historians#Zotero+Integration+Setup). I have my own import template, that focuses on the notes I made during reading:

```
# {{title}}

- [Bibliography](#bibliography)
- [Notes](#notes)
- [Abstract](#abstract)
- [Reading Notes](#reading-notes)

## Bibliography
{{bibliography}}

{% if abstractNote %}## Abstract
{{abstractNote}}{% endif %}

## Notes
{% persist "notes" %}{% endpersist %}
{% if markdownNotes %}{{markdownNotes}}{% endif %}

## Related
{% persist "related" %}{% endpersist %}
```

### …from websites
- From hypothes.is, just use the command `Hypothes.is: Sync Highlights`. That will sync all your notes and annotations that you've made online into your Obsidian files. It's buggy at times, but mostly works as intended.

## Writing
See [On Concentration and Reading Practice](journal/2023-03-06.md)

## Related
- [Research](notes/Research.md)