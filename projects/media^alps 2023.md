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
conda create --name chatterbot-env python=3.8
conda activate chatterbot-env
pip install chatterbot==1.0.4 pytz
```

- sqalchemy on windows needs fix [https://stackoverflow.com/a/66181432](https://stackoverflow.com/a/66181432)  
- find on windows needs alias [https://superuser.com/a/1219235](https://superuser.com/a/1219235)

## Tutorial
- [ChatterBot: Build a Chatbot With Python](https://realpython.com/build-a-chatbot-python-chatterbot)
- [About Chatterbot](https://chatterbot.readthedocs.io/en/stable/)

## Terminal Showcase
- `telnet towel.blinkenlights.nl`
- `telnet mapscii.me`
- `sampler --config ~/kDrive/Temporary/sampler.yml`
- https://github.com/agarrharr/awesome-cli-apps
- https://www.tecmint.com/best-linux-terminal-console-games/
- https://tilde.club/ and https://breadpunk.club/

## Schedule
### Saturday I
- Introduction
	- Shell and terminals, and why do they still exist
	- The written word as a foundation of todays computing
	- Two types of shell users
		- Sysadmins
		- hell-a-cute people https://j3s.sh/thought/write-posix-shell.html
- "Fun" with terminals
	- Fundamentals
		- man
		- history, ctrl + r
	- Navigate folder and files structures
		- pwd, ls, cd
		- relative and absolute path, invisible files
		- ., .., -, ~, /
		- [exercise] Explore a bit and see if you find your way around the places your usually hanging
	- Create, read and delete
		- touch, mkdir, open, cat, head, tail, rm (-r) !!!
		- [exercise] Create folder structure, some files, open and delete them
	- Move, Find and combine
		- 
		- cp, mv
		- [exercise] Find and cat over a folder structure I prepared.
	- System
		- top, kill
	- Fork Bomb for lunch
		- `:(){ :|:& };:`

### Lunch Break
 - See if anybody needs tech support regarding wsl/cmder/conda

### Saturday II
- Introduction nano
- Setup conda environment
- Chatterbot tutorial
	- https://realpython.com/build-a-chatbot-python-chatterbot/
- Producing some conversations by hand
- Cleaning up some chat data

### Sunday
- ?