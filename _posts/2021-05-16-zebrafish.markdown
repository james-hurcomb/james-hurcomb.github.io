---
layout: post
title:  "Master's project"
date:   2021-05-16 00:00:00 +0000
categories: paper
---

I've finished my Master's project.

My master's degree focussed on developing new ways to assess learning and memory in zebrafish. Unfortuantly, due to the impact of the pandemic, it's a little more computational than I originally intended. I developed some software that can be used to analyse novel object recognition test data—a common type of memory test, where you give an animal two objects to explore. You then switch out one of the objects for a new one, and if the animal remembers the previous objects they should spend more time exploring the new one. The [software is avaliable on github][za], on the off chance anybody has similar data they want to analyse. This project taught me a lot about working in Python: I've always been able to program in Python, but I never truly _understood_ the language until working on this.

![Image showing workflow. A video recording is taken of fish experiencing a NORT. Fish positions are logged using idtracker.ai, then this data is passed to my prgram, zebrafishanalyse which can plot graphs, calculate discrimination indexes, offers gui tools for ease of use, and the possibility to write custom scripts.](/assets/za.png)


[za]: https://github.com/james-hurcomb/zebrafish-analyse