---
layout: image-post
title: "On Documentation"
description: Why does it need to be so bad
date: 2021-2-13
image: /assets/images/Documentation/class-graph.png
author: Ritwik Patil
tags: 
  - Demo
  - Documentation
  - Pain
---

## [Demo](http://class-graph.herokuapp.com/graph/draguve)

I was working on a demo for a game in Unity when I had the age-old problem of forgetting how the code I wrote yesterday worked. So I decided then on I would write documentation on the code as I wrote it. But a few days later, I found myself in the same situation as I did a few days back. The documentation though helpful, still had me fundamentally staring at a wall of text. How does it matter if I read code or the description, In fact, one could argue reading the code might just be better there would be no information lost in translation in that case. The wall of text is nice to read when learning something new but it seems like a waste of time to read through multiple pages when I only need some specific information. This lead me to the thought that documentation instead of text should be instead more visual. 


Like the tweet below shows , technical documentation should be simple and exact.
<center><blockquote class="twitter-tweet"><p lang="en" dir="ltr">How a career in technical writing ruined me as a letter writer <a href="https://t.co/atLXrxRCXb">pic.twitter.com/atLXrxRCXb</a></p>&mdash; Karl Kovacs (@karlkovacs) <a href="https://twitter.com/karlkovacs/status/716653585686114304?ref_src=twsrc%5Etfw">April 3, 2016</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script></center><br>



The human brain is very good at processing images. Our visual processing centres are capable of interpreting highly complex visual data almost instantaneously. UML helps but the interface needs to be more interactive instead of being an image. If something allowed searching and tagging information it could seriously help things.[I couldn't anything similar so I thought I should make something just as a demo to test if the idea works](http://class-graph.herokuapp.com/graph/draguve).

There are lots of features that are missing here that could make this really useful but I think this serves as a good starting point to check if something like this is really useful or just too much work.

#### How to use it
```
Middle-Click and Drag to move around
Ctrl-Click to add new nodes
Hold Shift and Drag from one node to another to create a new link
Click any item to see and change information about that item 

```

#### Stuff that could be added?
* Better ways to select and move around information.
* Allowing multiple people to edit at the same time (Operational transformation).
* A Better way to add information that is intrinsic to the item(sub-items).