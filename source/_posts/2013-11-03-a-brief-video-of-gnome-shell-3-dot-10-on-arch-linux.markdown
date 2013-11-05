---
layout: post
title: "A brief video of GNOME Shell 3.10 on Arch Linux"
author: "Andrew Fader"
date: 2013-11-03 22:47
comments: true
categories: [Linux] 
---
Here's a video of the Arch Linux, GNOME and Cairo Dock setup I've been working with for the past few months.  Shown are a few of the customizations through the [extensions repository](https://extensions.gnome.org) that I think make this a very usable desktop environment, and one which can be extended easily and improve over time.
<!-- more -->
{% video /arch.ogv 720 405 %}

GNOME 3 introduces a 2-layer desktop concept including a navigational overview similar to OS X's dashboard, though not focused on widgets. One extension maps numbers to each window, which I can then select using alt+N as an alternative to what could be several alt+tabs. I have chosen, through another extension, to hide the top bar and only show it in the overview, which is bound to a hotkey as well as a pressure sensitive "hot corner" near the top of the screen. Since some of my other extensions are related to the top bar, this makes the overview a sort of widget layer as well. You'll note that hiding the top bar in OS X isn't even an option, so we can get more screen real estate when everything is hidden. I fully maximize the Clementine window near the end of the video, which also hides the dock.

Some of the other extensions include a "put windows" plugin comparable to SizeUp/ShiftIt for the Mac, and integration with media players like the excellent Clementine. Cairo Dock, a standalone program that provides an OS X-like dock UI, is also very customizable; I could probably devote several videos to exploring its options, shown briefly. It is currently set to "smart auto hide" which will hide only when overlapping a window, and not under the mouse. The Arch logo icon leftmost on the dock is an applications menu that groups by categories (not shown), like GNOME 2 or Windows. I briefly show a different applications menu, on the top bar in the overview, through an extension.

While Linus Torvalds famously attacked the GNOME 3 extensions repository for breaking extensions with the release of new versions, you can get old extensions to work on newer versions (sometimes) by editing a metadata.json file that is packed in with each extension (the extensions are written in JavaScript, I believe!). I think open bazaars like GitHub, Android Play Store and Arch's User Repository are the way of the future in software distribution, even though this means that users will sometimes experience bad or broken features with new releases. Taken together and once set up, I feel that this setup is comparable, if not significantly /more/ usable than similar ones on OS X. Those used to a more Windows-like experience can use different extensions or different configurations through KDE or XFCE.
