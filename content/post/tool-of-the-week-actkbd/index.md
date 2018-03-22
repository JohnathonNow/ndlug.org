+++
categories = ["lug"]
date = "2018-03-21T14:09:20-04:00"
description = "A helpful tool for binding actions to keyboard events"
draft = false
tags = ["lug", "tool of the week"]
title = "Tool of the Week: Actkbd"
toc = false

+++

As blog master, I figured I should do something before I am replaced next week, so I decided to take the club advisor's advice
and start a weekly column about helpful tools you might not have known about.

<!--more-->

If you're anything like me, you have two keyboards plugged into your desktop, because you own two, and what would you do with the
other one? You might also be in this situation if you plug a keyboard into your laptop. Whatever the case may be, you might have
some extra keys that you want to put to good use. [actkbd]() allows you to bind commands to keyboard events. My particular use case
involves having a spare keyboard and using the keys to control hardware peripherals (such as my speaker volume or projector).

Let's consider a simple example, where I want to turn my projector off. To do this, I would normally open up a terminal, and type
the command `xrandr --output HDMI-1 --off`. But that's tedious. I guess I could do something like 
`alias projoff='xrandr --output HDMI-1 --off'`, but even that is a bit much, as I need to have a terminal open, and have it in focus.
But if I'm in the middle of a YouTube video, I'd like to press one button, like the space bar, and have it turn my projector off.

