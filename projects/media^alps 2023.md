---
title: "media^alps 2023"
date: 2023-03-17
enddate: 2023-03-19
keywords: [coding ,workshop ,chatbot]
---
# media^alps 2023

## Abstract
Our medium is text, a bot our mirror. A bit less poetically: we'll attempt to create a chatbot, trained to speak like us. You will get an introduction to working with terminals, experience how it is to clean up raw data and our chatbots are coded with python. That means we will read and write a lot of text this weekend. You don't need coding experience to participate. The goal is to gain insights in what it could mean, to work with code. You need to bring your own laptop.

## Teach Reader
**Mac, Windows and Linux**
- Download and install Miniconda: https://docs.conda.io/en/latest/miniconda.html 

**Windows** (sorry…)
- Try to install WSL: https://learn.microsoft.com/de-ch/windows/wsl/install#install-wsl-command.
	- Start command prompt as administrator: https://praxistipps.chip.de/eingabeaufforderung-als-administrator-starten_34459
	- Paste `wsl --install`  into it and press enter. This should install Linux
- Alternatively install
	- **cmdr**: https://cmder.app
	- **nano**: https://anto.online/tips-and-tools/install-nano-text-editor-on-windows/

## Setup
- [WSL](https://learn.microsoft.com/de-ch/windows/wsl/install#install-wsl-command), [cmder](https://cmder.app/) als Backup
- nano, [nano on Windows](https://anto.online/tips-and-tools/install-nano-text-editor-on-windows/)
- [Miniconda](https://docs.conda.io/en/latest/miniconda.html)

```sh
conda deactivate
conda create --name chatterbot python=3.8
conda activate chatterbot
pip install chatterbot==1.0.4 pytz
```

- chatterbot==1.0.4 pytz works fine  
- sqalchemy on windows needs fix [https://stackoverflow.com/a/66181432](https://stackoverflow.com/a/66181432)  
- find on windows needs alias [https://superuser.com/a/1219235](https://superuser.com/a/1219235)

## Tutorial
- [ChatterBot: Build a Chatbot With Python](https://realpython.com/build-a-chatbot-python-chatterbot)

## Terminal Showcase
- `telnet towel.blinkenlights.nl`
- `telnet mapscii.me`
- `sampler --config test.yml`

## Schedule
### Saturday I
- "Fun" with terminals
	- Fundamentals
		- man, --help
		- history, ctrl + r
	- Navigate folder and files structures
		- pwd, ls, cd (.., -), relative and absolute path
		- [exercise] manually search for a specific file
	- Create, read and delete
		- touch, mkdir, cat, head, tail, rm
	- Combine and find
		- &&, where, find
		- [exercise] Find and cat/head/tail over a folder structure I prepared.
	- [optional] Shellscript
		- echo, ./, chmod, xargs, for and if
	- Fork Bomb for lunch

### Saturday II
- Setup chatterbot
	- Windows: Install wsl and cmdr
	- Install miniconda
	- More or less follow instructions
- nano
- Chatterbot tutorial
- Producing some conversations by hand
- Cleaning up some chat data

### Sunday
- ? 

## Ressources and thoughts
- https://realpython.com/build-a-chatbot-python-chatterbot/
- Why do terminals exist? https://www.quora.com/Why-are-terminals-and-command-prompts-still-used-in-operating-systems
