---
title: "iOS Shortcuts"
date: 2026-07-20
author: "vmah1ndra"
tags: ["iOS", "power user"]
---

One of the biggest hurdles on iOS systems for users that like poking around is the lack of finer controls for basic tasks. While this provides a seamless experience (and arguably more secure), I find myself first creating complicated workarounds for simple customization options before the actual task at hand. Recently, my favorite app for this is the iOS Shortcuts app.

Instead of specific apps (from somewhat sketchy sources) that copy some feature available by default on other OSes, why not code your own? The Shortcuts app is preinstalled on iOS and comes with a range of pre-made "shortcuts" that resemble macros or basic scripts. They work slightly faster, easier, and safer than trying to pop a terminal and isolate features or code them from scratch.

## Shortcuts

Shortcuts are automation features that use visual scripting and a library of isolated features from other iOS apps and operations. For example, you could make a shortcut that checks the date, your calendar for any saved events (say, birthdays), looks for an attached message (a birthday wish), and an attached contact (a friend's phone number). So this automation would send out birthday greetings on your app of choice.

The app also comes with the "Gallery," a large collection of shortcuts made by others. While these shortcuts could cause unexpected/undesirable behavior, the atomic actions performed by each step of the shortcut can only be actions permitted by iOS. You can also look through the steps and modify them. You can now also ask Shortcuts to create an action for you using AI features built into it, but we won't talk too much about that. Besides, this is a great way to get your feet wet in coding, it is simple and visual, checks for errors and tells you about it verbosely, and the end product is something you can practically use immediately.

## Make it yours

Here are some of my favorite (niche) ways to use shortcuts:

#### Strip EXIF Data
This includes photos taken on other devices.

#### Send out location/text/picture when battery levels are low

#### Video editing - loop videos, separate frames, create collages, make GIFs
Shortcuts often offer more than just the edit features on Photos, even if the Shortcuts action is provided by the same app.

#### Quickly convert videos to images to text, and save as a file
This one is useful in CTFs.

#### Join PDFs
No more Adobe

#### Actually turn off the Wifi and Bluetooth
This one is probably the most popular use of Shortcuts

## Code

Apart from being a good place to start coding for beginners, Shortcuts introduces concepts like loops, conditions, function arguments/outputs, and error handling methods. I find myself much more likely to immediately create a shortcut for a feature I find lacking on any app (like deleting old todo tasks) instead of losing my flow or hunting for an alternative app that contains this feature. Shortcuts often can replace most productivity app functions, or ones that nudge you to repetitive behaviors to form good habits. More on that next time.

Make wise clicks.
