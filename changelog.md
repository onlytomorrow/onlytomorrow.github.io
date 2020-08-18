---
layout: default
title: CHJ2020 dev log
permalink: /chj2020/
---

# CHJ2020 top secret progress report
this is the changelog for my game [*the adventures of crackhead jack: overdose edition*](https://store.steampowered.com/app/1328500?comment=ots), coming "soon" on Steam.
you can play the original version of the game (now with the subtitle *classic*) released in may 2016 (and updated until aug 2017) [here](https://gamejolt.com/games/the-adventures-of-crackhead-jack/148303), but i don't think you should play it cuz its unbalanced garbage

basically the game is an RPG parody where you play as a crackhead who is on a quest for a resupply of crack, which is surprisingly scarce for the game's setting.

progress reports are only from 2020-02-18 onward as thats when i started writing down what i was doing -- OD edition really started development around november 2019

if there are no updates, either i didn't want to put an entire update just for 1 change (i try to at least get *something* done for the game every day), or i lied about what i just wrote and [didn't do anything for the game that day.](https://www.youtube.com/watch?v=PEmqJBcQ2lg)

---

## 2020-08-17

#### delivery 3
- dialogue formatted
- edited RNG chances for plastic knife

#### straight edge
- fully implemented drug free items to make the run easier

---

## 2020-08-16

#### straight edge prep
- set up flags and trackers for 0.9.0.0 straight edge run
- add new items to accomodate straight edge players

#### delivery 2 polish
- scripted sequence completed
- bossfight scripted
- added new Burning state
- added special RNG state event for quest reward

#### fixes
- no skill message for IC weps
- enemy in Confused state trying weapon skill crashes the game
- some dialogue too long in delivery 2
- debrief no fade out post delivery 1

---

## 2020-08-15

#### delivery 1 polish
- scripted graceful umbrella descent
- added NPCs to gym

#### delivery 2 progress
- politician sprite
- office map added to MF doom W
- special voice acting

#### fixes
- NPC at monke village used a copy-pasted event
- pith shop weapons weren't assigned weapon skills

---

## 2020-08-13

#### continuing the delivery quest
- introducing a new boss, special moveset, sprites
- started eventing the first act of the quest

---

## 2020-08-12

#### delivery quest stuff
- formatting WIP dialogue to ExternalText...
- new key items for quest

---

## 2020-08-11

#### delivery quest: prep
- quest start map w/ shop
- new sprites for a bunch of new characters
- tilesets for quest-specific maps
- four new weapons

---

## 2020-08-10

#### factory quest: post content
- added a boss rush area

#### other
- added a new shop in the Inner Tower

---

## 2020-08-09

#### more factory quest cleanup
- add vignette in quest area
- get rid of blue fogs for transition at fac ent
- adjust timing in the burning room
- added skills for special enemies

#### fixes
- embodiment sprite gap
- dream didnt fade out correctly
- player could leave after seeing map transition
- same issue^ but after using key item
- fog didnt fade out correctly
- key item could be used outside of designated map

---

## 2020-08-08

#### factory quest cleanup / fixing
- shadow gap in battle sprite
- fade out mistimed with screen fade
- wrong r10 -> lot transfer
- boss appearance is too fast

#### special dream animation
- all done with pictures. somehow easier than editing it in Vegas


---

## 2020-08-07

#### factory quest: tunnels cont.
- all dialogue formatted for ExternalText
- map names formatted ^
- all room tilesets completed
- several scripted events completed

---

## 2020-08-06

#### factory quest: b1/airlock
- second disappearance event setup
- airlock visual effects and door timings

#### factory quest: ???
- special battle event setup
- obelisk/beacon event animations

#### factory quest: tunnels
- setup transfer events
- rail car tile polish

---

## 2020-08-05

#### factory quest: entrance events
- fog setup in route 10 & entrance A
- setup tar entrance and transition

#### factory quest: f1
- scaffolding disappearance events
- new enemy/troops

---

## 2020-08-04

#### changes
- set up new maps in database
- reduced chances of stupidly difficult enemies at the starting area
- more tileset creation

---

## 2020-08-01

- setting up dialogue for the new sidequest. script's written
- new tiles for this sidequest

---

## 2020-07-29

- added five new weapons and skills
- started a sidequest i'd been meaning to add since last year

---

## 2020-07-28

#### changes
- added Yanfly's Common Event shop
- reduced chances of some enemies at the start of the game, shit's too hard lol
- set up Pitheor's Weapons and Scum Skills

#### fixes
- cabin boxes have infinite items

---

## 2020-07-24

#### changes
- some dialogue in OD quest

#### fixes
- some cut off text in pity quest dialogue

---

## 2020-07-23

#### changes
- added slot machines to Strong Camp
- added more steam achievements
- started and completed yet another sidequest

#### fixes
- Old Man sprite had no shadow

---

## 2020-07-22

#### changes
- polished and finished the Meth Mainland new camp

#### fixes
- Methropolis sign had no text

---

## 2020-07-20

#### changes
- new Meth Mainland camp with an optional boss
- added more NPCs in prev. side quest area

---

## 2020-07-19

#### changes
- remove SSA=on in Item Get events
- moved some boss loot to after the battle is done
- adjusted some icons

#### fixes
- finally fixed a problem where shop tiers weren't working based on location
- some transfer events were still transfering to old locations

---

## 2020-07-18

#### changes
- rebalance MONKE enemies
- added choice to load from Gameover
- new sidequest added in Forests
- new skills and special items

#### fixes
- some enemies weren't in the ExternalText db

---

## 2020-07-17

#### changes
- changed some Sodatown dialogue
- sell more items at Sodatown/MRPS
- added nag system
- started work on MONKE sidequest

#### fixes
- KY started fight when re-entering area
- Logic's portrait had reversed text

---

## 2020-07-16

#### changes
- changed some dialogue in a late game section, particularly some jokes, they're not funny.
- did a bunch of nerfs and stuff after watching someone play through the game and get their ass kicked by a certain boss.

#### fixes
- fix a typo i followed on a spreadsheet

---

## 2020-07-15

- view all the changes at the [Steam Log]({{ site.url }}/stcl/)

---

## 2020-07-10

#### fixes
- player stuck when returning to cruise room
- add varying dialogue for some Sodatown NPCs

---

## 2020-07-06

#### changes
- adjusted Item menu navigation

#### fixes
- player can't jab when no weapon is equipped

---

## 2020-07-05

#### changes
- new quests

#### fixes
- SE char is flipped
- new Fizz Boss mix
- new APE mix
- add top hat to an enemy
- nerf a certain boss healing
- KC med is called Cave o Larpers
- FG disappears after giving one item (from common event ssa=on)

---

## 2020-07-04

#### changes
- added proper notif for losing SH on escape
- added events to new area

---

## 2020-07-03

- new area maps
- new enemy sprites
- Fizz Boss theme complete (OST is at 50%!)

---

## 2020-07-01

#### changes
- final bossfight is done
- buffed Vape Hit
- Powdered Projectiles now has 15% stun chance
- more endings...
- new character in Paradise Caves
- added map display names for all bench locations
- reduced flashing effects on all animations
- nerfed agents and some encounters at htp

#### fixes
- update MONKED bots after CFE unlock
- teleport from Lab is bugged
- CFE Lab teleport waits for KY before playing anim
- HTPE fade in wrong
- marble typos
- some HTP events were still transferring to old

---

## 2020-06-30

#### fixes
- himoff dialogue text appears too long in hand-in scene
- text typo at MRPS pub

#### changes
- APE's iron defense is too powerful, nerfed
- APE's mercury shower is too powerful, nerfed
- increase ninja exp payout
- sell more accessories at stoner shack

---

## 2020-06-27 - 2020-06-29

finally started pre-alpha testing

#### bug fixes
- typo in harmless man text key
- depths room 3 cans used old eventing
- removed old sound files
- missing SE at slots
- enemies spawn under player, pop in
- enemies don't initiate battle on forced respawn
- respawn item didn't work at all
- soda fields scene never starts

#### changes
- renamed Jack's limit break
- reiterate what you are looking for in depths
- add some Steam achievements
- add explanations for a boss' attack pattern
- new Game Over screen
- added new music to some bosses and maps
- added respawn item SE
- new encounter SE
- work on last bossfight (new animations and skills)

---

## 2020-06-26

- Crackhead Jack is Coming Soon on Steam.

---

## 2020-06-25

#### trailer work
- rerecord Townsplace sections with updated tiles
- sync with title music

#### fixes
- methropolis pub was using sodatown sprites
- bazooka sprite has extra pixels
- change some weapon flashes in animation

---

## 2020-06-24

#### fixes
- remove unused alert balloon at start
- remove unused shop tutorial
- wrong shop tier at knight's crossing
- incorrect text keys in homeless escape

---

## 2020-06-20

- fixed some frustrating issue about a black screen thats unerasable on load at a certain bench

---

## 2020-06-19

#### fixes
- once again fixing some cutscenes that refuse to work, that's all
- no fade in loading CF bench
- player not turning left in CA scene
- adjust length of transport flash

---

## 2020-06-17

#### changes
- added battlebacks and some maps

#### fixes
- reorganized CF portal scene
- polished some cutscenes

---

## 2020-06-16

#### changes
- new character sprites for the final scenes

#### fixes
- fog Z layers crash the game after using psychs in battle (fogs can't be added to the battle scene)
- the fix for the above issue also broke the Flashy Effects toggle! i love having to fix this toggle after every test run
- missing outlines for an animation
- typos in some text keys caused skipping of dialogue
- Blunt Roller enemies were not holding blunts, but joints. tf?
- ExternalText was storing old display names for unused maps. they eventually got replaced with different ones so they were showing the wrong name

---

## 2020-06-15

i gotta get a trailer done for this game really soon fuck

#### lag hell
up to this point, CHJ's largest map was the Highway to Paradise (HTP), but it still had less than ~150 events. but the game usually kept up, staying usually above 58 FPS, with some stutters because events. now with new and slick and cool animations the game dips to 30 FPS, especially on HTP. i can't use the nice looking things without low end pc's suffering, so my excuse will be "the technology just isn't there yet."

for now we must deal with scrolling fog images that work well enough.

with everything together (including the animations), not only was the scene not flowing well, but the game pretty much slowed to a crawl when the animations kicked in. RMVXA doesn't natively support walk n' talks because that definitely isn't something that developers want to do. so with scripts and processing move routes every frame, it looked weird from the beginning.

- scrapped the final cutscenes i wrote because of ^
- move marble variable change to the marble event itself instead of running in a parallel process. i blame my 14 year old self.
- split HTP into 6 sub maps. that pretty much fixed all the FPS issues on that map with the addition of the enemy encounters.

#### other fixes
- disabling Flashy Effects didn't stop the new animations, because conditional branches on parallel processes are jank
- no other fixes, i spent 8 hours today trying to mess with common event logic figuring out the lag stuff

---

## 2020-06-12

#### animation fixes
- one overlay is too bright, added transparency
- copy pasting script calls = inevitable typo and cause game crash haha
- add looping tint adjust
- cleaned up common events because it is not organized 

---

## 2020-06-07

#### fixes
- save information uses database map display name instead of reading from ExternalText
- some characters are invisible in CF
- a character is not loaded in the right spot from bench

---

## 2020-06-04

#### fixes
- make entrance priority on map consistent across all maps
- bad HTP tiling

#### changes
- rewrite some le cringe dialogue
- outlined battle animations in white because its hard to look at in certain battlebacks

---

## 2020-06-03

#### fixes
- bad character sprite at teleport cutscene
- wrong fade in for CFE
- bad death sprite

---

## 2020-06-02

#### fixes
- updated bench at late game map
- loop count error for bot teleport
- missing SE crash (i missed a couple of events that still referred to old SE)
- player can mess up a cutscene after it's done
- bad sprite switching for TA death event
- one too many button presses after a boss message
- bad market sprite

---

## 2020-06-01

#### fixes
- incorrect fade in from a certain transfer event
- a messed up cutscene process order
- incorrect face portrait for a certain character
- characters not correctly leaving cutscene
- don't show MAT / MDF in shop and item layouts

#### changes
- edited character sprites
- new BattleStart splash
- added battleback for a boss

---

## 2020-05-28

- steam progress.

#### fixes
- updated old bench event in fields
- edited a boss end
- removed bad alert balloons

#### changes
- renamed some enemies

---

## 2020-05-25

#### fixes
- removed unused battler sprites
- removed references to Hardmode
- fixed a typo bug in a shop check
- fixed an obstacle issue in inner tower after returning from F1 R1

#### changes
- added more bench locations
- new tutorial (again)
- getting currency term is now consistent across a bunch of dialogue
- renamed some enemies and bosses

---

## 2020-05-23

- removed Hime's Counted Loops because of save incompatibility mid-loop
- have to make a new save pack now because of it...

---

## 2020-05-22

- steam store progress
- continued final cutscene scripting

---

## 2020-05-21

- added a new story cutscene after one of the early bosses

---

## 2020-05-15

- set up move routes and fixed some bad tiles
- removed all unused sound files (game is now ~90mb atm)

---

## 2020-05-14

- text conversion 100%!
- sorry for the lack of updates. today marked the day of 4 years since the original crackhead jack was released onto GameJolt.
- there's not much to write here, as they all are part of stuff i actually don't want to spoil. but it'll be done.
- once the final cutscenes and events are finished, i'm going to playtest a bit, then start the steam application process to get wider playtesting done. 

this took way longer than i expected, comes as no surprise honestly. this last part is the most boring part, and sooner or later i'll be back to binging nights working on this game again when playtesting starts....

---

## 2020-04-27

- text conversion 99.5%
- final section of the game now...
(sidequests and new content havent even been close to completed, and music is not done)

---

## 2020-04-25

- text conversion ... 99%? the rest is all new content now
- fixed a shitton of issues with the animations and inevitable frame drops that came along with it
- new character portraits background
- SFX changes

---

## 2020-04-24

- text conversion 96%
- juicy new animations and overlays that i spent way too much time trying to get to work
- add [Hime's Counted Loops](http://himeworks.com/2013/03/counted-loops/) because VXA loops SUCK!!!!!!
- redone cutscenes
- redone quest

---

## 2020-04-22

- text conversion 94%
- new map
- fixed cutscenes
- updated character portraits

---

## 2020-04-21

- text conversion 92%
- rewrote the intro again
- new character scenes
- new encounter splash screen
- fixed old map names

---

## 2020-04-18

- text conversion 85%
- new map for route 11, 12
- new laboratory map
- new events for NPC buildings in the new region
- rewrote the cult town section 
- removed old maps with quests that wont be in the final game
- fixed some text 
- fixed broken event branches
- fixed a lot of script stuff that doesn't matter to you

---

## 2020-04-06

- text conversion 70%
- got rid of some old events
- 3 new maps for sidequests
- revamped town maps, boss fights

---

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
