---
layout: default
title: CHJ2020-i
permalink: /chj2020/issues/
---

# CHJ2020 issue tracker

[*changelog*]({% link changelog.md %})

---

- figure out a way to set the user to default to themselves rather than Jack when trying to consume an item

- `ExternalText` doesn't wrap text in RPGMaker's `Window_Help` class that displays item/skill descriptions in the main menu. 
	- `ExternalText` adds new methods in `Window_Base`, the superclass of `Window_Help`, though only involving removing escape characters.
		- fix needs to be added that adds the `wrap_text` method and `too_wide?` check to `Window_Help` or `Window_Base`, taken from the `Game_Message` changes in the `ExternalText` script
		- ive literally never coded in Ruby before so this has stumped me for more than a month now lmaooo
	- unlike regular dialogue window keys supporting newlines in their files, `Window_Help` seems to completely ignore these, or adds an extra new line. since the help window is only 2 lines long, the second line in the text key doesn't show up at all in-game.