---
layout: post
title:  "Git(Hub)'s Missing Feature"
date:   2016-01-08
categories: Open Source, git, GitHub, collaboration
---

If you've ever tried to browse the files in a GitHub repository to try to figure out how to contribute to a project, you probably already totally agree with me. I'm surprised it hasn't been implemented long ago, or at least talked about all the time:

File descriptions!

Check out the image below. Imagine you're making you're perusing the files in GitHub's [Atom](github.com/atom/atom) project for the first time, hoping to fork it and make fix a certain bug or add a specific feature.

![Bad descriptions]({{ site.url }}/assets/useless-descriptions.png)

Look next to each file name, and what do you see? The mandatory commit message that git enforces (and I'm glad it does) when you make a change. Now, being new to the project, from your perspective, its current state might as well be its initial state. You don't really care who changed what and what they were doing when they changed each file. What you really want to know, why do these files exist? How is the functionality encapsulated in the file structure?

You want to know which file to hack on to make your changes! And you don't want to have to rely on a combination of carefully chosen filenames and a lengthy exploration of the project's file structure to find out.

I can't tell you how many times, when looking at an unfamiliar project, I've absentmindedly looked at the commit messages next to the files, thinking they would hold the key to deciphering the mysterious purposes of the files.

I was going to include an alternate image...one where I doctored the screen shot to include file descriptions, but alas, I'd have to spend hours reading the files (and incidentally learning CoffeeScript) to figure out what to write there.

I really think this one addition to git(hub) would ease the way for those who want to get started contributing to projects.
