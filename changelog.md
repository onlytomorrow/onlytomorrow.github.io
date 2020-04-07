---
layout: default
title: CHJ2020
permalink: /chj2020/
---

# CHJ2020 top secret progress report
this is the changelog for my game *the adventures of crackhead jack: overdose edition*, which hopefully i'll release on Steam mid 2020.
you can play the original version of the game released in may 2016 (and updated until aug 2017) [here](https://gamejolt.com/games/the-adventures-of-crackhead-jack/148303), but i don't think you should play it cuz its unbalanced garbage

basically the game is an RPG parody where you play as a crackhead who is on a quest for a resupply of crack, which is surprisingly scarce for the game's setting.

progress reports are only from 2020-02-18 onward as thats when i started writing down what i was doing -- OD edition really started development around november 2019

[*issue tracker*]({% link issues.md %})

---

## 2020-04-06

- text conversion 70%
- got rid of some old events
- 3 new maps for sidequests
- revamped town maps, boss fights

## 2020-03-27

- text conversion 65%

#### texture changes

- new bot sprite
- building tilesets for region 2
- new state icons
- edited some battler sprites

#### misc changes

- changed all shop buildings' counter to be straight ahead of the door
- add [Yanfly's Shop Options](https://yanflychannel.wordpress.com/rmvxa/menu-scripts/ace-shop-options/) and [Hime's Shop Manager](http://himeworks.com/2013/02/shop-manager/) to improve the s h o p p i n g    e x p e r i e n c e
    - new shop layout, removed the extra choice box in wep shop
    - can now equip wep/armour at the shop window

#### fixes

- band-aid fix for descriptions involving variables and newline code rather than actually trying to edit the script lol
- fixed NPCs not always walking into transfer event in the same way as the player
- a bunch of other stuff that doesnt matter to you :)

[♪](https://i.vgy.me/1BHDDC.jpg)

---

## 2020-03-26 

- text conversion 60%
- section 5 complete, now onto section 6 (next region)

#### texture changes

- new overworld sprites for cruise ship
- new icons for new states
- update icons to a more consistent colour scheme
- cruise boss
    - new sprites for boss and enemies
    - new attack animations

#### misc changes

- new menu and battle SE
- rebalanced special skills and bosses
- add [Yanfly's Combat Log Display](https://yanflychannel.wordpress.com/rmvxa/battle-scripts/combat-log-display/) as an extra option during battles

[♪](https://i.vgy.me/urha1W.jpg)

---

## 2020-03-25 

- text conversion 45%
- now on section 5

#### texture changes

- made a new control info graphic
- added more battle animations
    - item consumption and limit breaks
- more consistency on all icons' bg

#### issue fixes

- fixed sprite animation disappearing too fast ahead of screen fade out on switch activation
- fixed bad fadeout of special lighting in some maps
- fixed NPCs not completely following route into transfer event
- add [Lone Wolf's Gamepad Extender](https://forums.rpgmakerweb.com/index.php?threads/gamepad-extender-v1-1-2-20-2015.1284/) and [Jono99's GE Game Adapter](https://forums.rpgmakerweb.com/index.php?threads/ge-game-adapter.69589/) for better XInput support
- add [Theo's Insane Anti-Lag](https://www.rpgmakercentral.com/topic/28492-theo-insane-anti-lag-version-11-added-page-check-enhancer/) to fix stuttering issues in major maps

[♪](https://i.vgy.me/KlJhCs.jpg)

---

## 2020-03-24

#### new sodatown: complete list of changes

- new sidequest involving stoners and thieves
    - new enemy and boss type
    - new (temporary) party member
        - cannot be controlled by player tho
- new sidequest intro involving lots of meth
    - new enemy type
    - new key item
    - more secrets
- added new healing items
- added new melee weapons
- added new area (sidequest related)
- sodatown now has actual npcs and houses

[♪](https://i.vgy.me/n0XBYw.jpg)

---

## 2020-03-23 

- text conversion 40%
- section 4 complete
    - added enc to caves
    - rewrite dialogue events
    - fixed save points
    
#### sodatown changes

- updated dialogue
- reworked market shop
- updated grave/dealer events
- updated box/barrel/sign sprites
- added Galv's [Visibility Range](https://galvs-scripts.com/2013/05/30/visibility-range/) and [Move Route Extras](https://galvs-scripts.com/2013/03/11/move-route-extras/) scripts for improving cutscenes

[♪](https://i.vgy.me/p4qivn.jpg)

---

## 2020-03-22

- text conversion 37%, begin reformatting section 4
- fixed an issue where buff/debuff levels past 3 showed incorrect icons
- updated some sprites
- added new menu SE

---

## 2020-03-21

- text conversion 35%
- finish section 3, needs testing
    - new dialogue, events, cutscenes, area redone

---

## 2020-03-19

- text conversion 30%
- move changelog from rentry to github pages
    - rentry has a 10k character limit and this changelog almost has 8k
    
---

## 2020-03-12

- text conversion 26%
    - reformatted grave robbing
- begun section 3
- changed drug dealer products to be slightly altered from clean pharmacy products... obvious side effects

---

## 2020-03-11

- text conversion 24%
- finished section 2b (homeless shelter optional section)
- added working slot machines with variable bets lmaooo
- fixed(?) a long lasting issue of encounter balloons still appearing when enemies were invisible... might still need more testing

---

## 2020-03-10

- text conversion 23.3%
- added the Confusion state
- implemented [Yanfly's Buff & State Manager](https://yanflychannel.wordpress.com/rmvxa/gameplay-scripts/buff-state-manager/) script for state adjustment

---

## 2020-03-09

- fix issues with encounter events appearing visible and interacting with player after battle is complete
- playtesting: game might be too grindy at the beginning still, adjust exp payouts

---

## 2020-03-07

#### weapon status effect variety & rebalancing

- added various status effects that have a chance of applying when using certain categories of weapons in the game
- reformatted item/skill descriptions, as well as internal `Vocab` strings to keep everything consistent
- fixed an issue with item events having a `Through` tag after an interaction
- added new states: Bleeding, Paranoia, as well as edited icons

---

## 2020-03-06

#### more enemy/level progression rebalancing

- internally organized enemies into tiers, adjusted ATK/DEF/AGI/EXP/Gold ranges for each tier
  - their stats are now slightly better than where the player should be in terms of level progression

---

## 2020-03-05

#### rewrite section 2b of the game

- text conversion 23%
- enemy tournament sidequest, rewrite dialogue, create a new map to fit

---

## 2020-03-04

#### start completely rebalancing the early game enemies
- new damage formula for all attacks
	- `x * atk^2 / (atk+def)`, where `x` is essentially an attack's adjustable power number
- enemies too easy to kill and too weak to kill the player...

---

## 2020-03-03

- text conversion 21% maybe
- added a gambling machine for a certain area in the early game
- fixed up ugly looking sprites

---

## 2020-03-02

- text conversion 20.2% idk lol
- added new police officer characters
	- new overworld sprites, character portraits, etc
	- script in a cutscene that plays after turning in the 1st quest from section 2

---

## 2020-02-28

- text conversion at 20%
- story related changes no smoilers
	- implement Tsukihime's [Preserve Data](https://www.rpgmakercentral.com/topic/12621-preserve-data/) script to add some fourth wall breaking in the game story lol
- fixed buggy as hell encounter system
	- enemies popping in and out, not respawning on time (2400 frames / 40 seconds)
	- alert balloons not consistently showing
- with the animation sprites redone, now to reanimate the actual battle animations using the new sprites
	- had to do this frame by frame for around 20 animations, only 50% complete (20 animations out of 66 total) since i didn't finish drawing all of the new sprites (postponing that for when i finish text conversion)

---

## 2020-02-27

- text conversion is like 15% complete at this point
- start rewriting the first major boss section of the game, redoing tilesets and overhauling the entire section pretty much

---

## 2020-02-26

- still converting everything to .txt, first town in the game is almost fully converted
- reorganize common events, they originally looked like a mess
- rewrite the game's tutorial, cuz it sucks

---

## 2020-02-25

#### create new iconset

- the old game used the default rpgmaker iconset so i decided to make original icons
	- this took a long ass time with how tiny the icons are, and making icons for a ton of skills and items in the game

---

## 2020-02-24

[battle animations: before and after (image)](https://karukyu.s-ul.eu/5qrJSoD4.jpg)

- (turns out the shrooms and jack limit animation sprite still isn't changed in that grid, will fix lol)
- this had to be redone because the original game used random images from google images and i don't have the rights to that
	- this took a long ass time btw lol
- still converting everything to .txt for External Text
- new sound effects for animations as well

---

## 2020-02-23

brand new and shiny [title screen](https://www.youtube.com/watch?v=TS4KWdbQcIg), with original music :)

- implement Tsukihime's [Reference Events](http://himeworks.com/2013/10/reference-events/) script to polish encounter events and make it universal
	- this makes it so that i don't have to edit every event that is the same. instead i can edit one event and it affects all child events

---

## 2020-02-21

#### overhaul random encounter system

- the old random encounter system was basically: player walks around the map and theres just a chance they get thrown into a battle
- new system: enemies are visible on the map, and when player is near, they chase the player. upon touching the player, a battle starts
	- created a new sprite set for having on-map enemy encounters that the player can actually see

---

## 2020-02-18

#### implement Enelvon's [ExternalText](https://github.com/sesvxace/external-text) script

- overhauls the program's default text editing system
	- with this script text automatically wraps in message windows (which isn't a default feature for whatever reason)
	- can be edited through easy to organize text files
	- adds support for multi language translations
- started converting in-game messages to .txt files (very long and tedious process, this involves rewriting all text in the game into .txt files)
