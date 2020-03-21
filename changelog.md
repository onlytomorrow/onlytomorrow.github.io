---
layout: default
title: CHJ2020
permalink: /chj2020/
---

# CHJ2020 top secret progress report
this is the changelog for my game *the adventures of crackhead jack: overdose edition*, which hopefully i'll release on Steam mid 2020.
you can play the original version of the game released in 2016 (and updated until 2018) [here](https://gamejolt.com/games/the-adventures-of-crackhead-jack/148303), but i don't think you should play it cuz its unbalanced garbage

basically the game is an RPG parody where you play as a crackhead who is on a quest for more crack, some small youtubers have done lets plays of the old game too lol

---

progress reports are only from 2020-02-18 onward as thats when i started writing down what i was doing -- OD edition really started development around november 2019

---

## current issues that i still gotta fix
- fix debuff icons

- the `ExternalText` script doesn't wrap text in RPGMaker's `Window_Help` class that displays item/skill descriptions in the main menu. 
	- `ExternalText` adds new methods in `Window_Base`, the superclass of `Window_Help`, though only involving removing escape characters.
		- fix needs to be added that adds the `wrap_text` method and `too_wide?` check to `Window_Help` or `Window_Base`, taken from the `Game_Message` changes in the `ExternalText` script
		- ive literally never coded in Ruby before so this has stumped me for more than a month now lmaooo
	- unlike regular dialogue window keys supporting newlines in their files, `Window_Help` seems to completely ignore these, or adds an extra new line. since the help window is only 2 lines long, the second line in the text key doesn't show up at all in-game.

## 2020-03-21
- text conversion 35%
- finish section 3, needs testing
    - new dialogue, events, cutscenes, area redone

## 2020-03-19
- text conversion 30%
- move changelog from rentry to github pages
    - rentry has a 10k character limit and this changelog almost has 8k

## 2020-03-12
- text conversion 26%
    - reformatted grave robbing
- begun section 3
- changed drug dealer products to be slightly altered from clean pharmacy products... obvious side effects

## 2020-03-11
- text conversion 24%
- finished section 2b (homeless shelter optional section)
- added working slot machines with variable bets lmaooo
- fixed(?) a long lasting issue of encounter balloons still appearing when enemies were invisible... might still need more testing

## 2020-03-10
- text conversion 23.3%
- added the Confusion state
- implemented [Yanfly's Buff & State Manager](https://yanflychannel.wordpress.com/rmvxa/gameplay-scripts/buff-state-manager/) script for state adjustment

## 2020-03-09
- fix issues with encounter events appearing visible and interacting with player after battle is complete
- playtesting: game might be too grindy at the beginning still, adjust exp payouts

## 2020-03-07
#### weapon status effect variety & rebalancing
- added various status effects that have a chance of applying when using certain categories of weapons in the game
- reformatted item/skill descriptions, as well as internal `Vocab` strings to keep everything consistent
- fixed an issue with item events having a `Through` tag after an interaction
- added new states: Bleeding, Paranoia, as well as edited icons

## 2020-03-06
#### more enemy/level progression rebalancing
- internally organized enemies into tiers, adjusted ATK/DEF/AGI/EXP/Gold ranges for each tier
  - their stats are now slightly better than where the player should be in terms of level progression

## 2020-03-05
#### rewrite section 2b of the game
- text conversion 23%
- enemy tournament sidequest, rewrite dialogue, create a new map to fit

## 2020-03-04
#### start completely rebalancing the early game enemies
- new damage formula for all attacks
	- `x * atk^2 / (atk+def)`, where `x` is essentially an attack's adjustable power number
- enemies too easy to kill and too weak to kill the player...

## 2020-03-03
- text conversion 21% maybe
- added a gambling machine for a certain area in the early game
- fixed up ugly looking sprites

## 2020-03-02
- text conversion 20.2% idk lol
- added new police officer characters
	- new overworld sprites, character portraits, etc
	- script in a cutscene that plays after turning in the 1st quest from section 2

## 2020-02-28
- text conversion at 20%
- story related changes no smoilers
	- implement Tsukihime's [Preserve Data](https://www.rpgmakercentral.com/topic/12621-preserve-data/) script to add some fourth wall breaking in the game story lol
- fixed buggy as hell encounter system
	- enemies popping in and out, not respawning on time (2400 frames / 40 seconds)
	- alert balloons not consistently showing
- with the animation sprites redone, now to reanimate the actual battle animations using the new sprites
	- had to do this frame by frame for around 20 animations, only 50% complete (20 animations out of 66 total) since i didn't finish drawing all of the new sprites (postponing that for when i finish text conversion)

## 2020-02-27
- text conversion is like 15% complete at this point
- start rewriting the first major boss section of the game, redoing tilesets and overhauling the entire section pretty much

## 2020-02-26
- still converting everything to .txt, first town in the game is almost fully converted
- reorganize common events, they originally looked like a mess
- rewrite the game's tutorial, cuz it sucks

## 2020-02-25
#### create new iconset
- the old game used the default rpgmaker iconset so i decided to make original icons
	- this took a long ass time with how tiny the icons are, and making icons for a ton of skills and items in the game

## 2020-02-24
![before&after](https://karukyu.s-ul.eu/5qrJSoD4.jpg)
- (turns out the shrooms and jack limit animation sprite still isn't changed in that grid, will fix lol)
- this had to be redone because the original game used random images from google images and i don't have the rights to that
	- this took a long ass time btw lol
- still converting everything to .txt for External Text
- new sound effects for animations as well

## 2020-02-23
#### brand new and shiny [title screen](https://www.youtube.com/watch?v=TS4KWdbQcIg), with original music :)
- implement Tsukihime's [Reference Events](http://himeworks.com/2013/10/reference-events/) script to polish encounter events and make it universal
	- this makes it so that i don't have to edit every event that is the same. instead i can edit one event and it affects all child events

## 2020-02-21
#### overhaul random encounter system
- the old random encounter system was basically: player walks around the map and theres just a chance they get thrown into a battle
- new system: enemies are visible on the map, and when player is near, they chase the player. upon touching the player, a battle starts
	- created a new sprite set for having on-map enemy encounters that the player can actually see

## 2020-02-18
#### implement Enelvon's [ExternalText](https://github.com/sesvxace/external-text) script
- overhauls the program's default text editing system
	- with this script text automatically wraps in message windows (which isn't a default feature for whatever reason)
	- can be edited through easy to organize text files
	- adds support for multi language translations
- started converting in-game messages to .txt files (very long and tedious process, this involves rewriting all text in the game into .txt files)