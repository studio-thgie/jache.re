---
title: "media^alps 2023"
date: 2023-03-17
enddate: 2023-03-19
keywords:
	- coding
	- workshop
	- chatbot
---
# media^alps 2023

## Abstract
Our medium is text, a bot our mirror. A bit less poetically: we'll attempt to create a chatbot, trained to speak like us. You will get an introduction to working with terminals, experience how it is to clean up raw data and our chatbots are coded with python. That means we will read and write a lot of text this weekend. You don't need coding experience to participate. The goal is to gain insights in what it could mean, to work with code. You need to bring your own laptop.

## Setup
- iTerm, cmder
- nano
- Anaconda

```sh
conda create --name chatbot-env python=3.8
pip install chatterbot==1.0.4 pytz
```

- chatterbot==1.0.4 pytz works fine  
- sqalchemy on windows needs fix [https://stackoverflow.com/a/66181432](https://stackoverflow.com/a/66181432)  
- find on windows needs alias [https://superuser.com/a/1219235](https://superuser.com/a/1219235)

## Schedule
### Saturday I
- Setup chatterbot
	- More or less follow instructions
- Fun with terminals
	- Folder and files structures
	- Navigate and find
	- Create and edit
	- Fork Bomb for lunch
### Saturday II
- Chatterbot tutorial
- Producing some conversations by hand
- Cleaning up some chat data
### Sunday
- 

## Ressources and thoughts
- https://realpython.com/build-a-chatbot-python-chatterbot/
- Why do terminals exist? https://www.quora.com/Why-are-terminals-and-command-prompts-still-used-in-operating-systems
