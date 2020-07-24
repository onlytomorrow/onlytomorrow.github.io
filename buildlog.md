---
layout: default
title: CHJ-ST change log
permalink: /stcl/
---

# Crackhead Jack Steam Version (CHJ-ST) change log

The Steam version is currently on **0.7.3.0**. This log has spoilers for the game's story if that matters to you.

### Milestones

**0.7.0.0** - Crack quest: main story playable from start to finish  
**0.8.0.0** - Side quests: add Factory and Bug Spray quests  
**0.9.0.0** - Straight edge: add Straight Edge mode  
**1.0.0.0** - Steam game ready: OST complete  

---

### v 0.7.3.0 (2020-07-24)

#### Minor

- Added new side quest in Methropolis
- Added new side quest deep in the Meth Forests
- Added new optional boss somewhere in the Meth Forests
- Added choice to load directly from the Gameover screen
- Added a secret nag event
- Added achievement for robbing all graves
- Added a "Witness" state that prevents you from getting XP from auto-win battles
- State Relief, Pain Relief, and Amphetamines are now sold at Sodatown
- Pain Relief+ and Amphetamines+ are now sold at Methropolis
- Amphetamines++ are now sold at Knight's Crossing
- Added new item "Asset Needle! Aid Liquid!"
    - costs 420 SH, +20% EXR, 1.2xATK for 120 steps
    - "Asset Needle! Aid Liquid!!+": 820 SH, +30% EXR, 1.2xATK for 420 steps
- Reduced dodge chance for Fizz Boss (35% -> 30%), DEF (60 -> 55)
- Fizz Boss now has a 10% chance of dropping Agility Shoes
- Increased base M.O.N.K.E.'s MHP (300 -> 800), DEF (15 -> 25), XP (90 -> 120)
- Reduced max turn length of Stun effect (3 turns -> 2)
- Adjusted constant in escape rate formula (0.6 -> 0.8)
    - this constant is multiplied with `(party's avg AGI / enemy's avg AGI)`
- Moved some boss loot to after their battle
- Changed some dialogue in a late game scene
- Changed some battle log messages
- Changed death state icon

#### Fixes

- Accidentally followed an outdated achievement key in my spreadsheet lol
- Saving at Soda Fields didn't show map name in Load menu
- P.I.T.Y. shelter slot machine used outdated events
- Notif wasn't showing after getting transported from a certain secret area
- A certain character's portrait had reversed text
- Some enemies weren't in the ExternalText database
- A long running mystery of why internal shop tiers weren't working in Meth Mainland has been resolved
- Remove a self switch turning on in a widely used common event
- Pharma NPC wasn't properly tracking shop use
- NP5 description was missing italics
- Scrunched ugly ass text at Knight's Crossing tents
- M.O.N.K.E.s in forests were using regular random encounter pool
- Equips shop was still called "Gear Shop" in welcoming
- Methropolis sign had no text
- Old Man sprite had no shadow

---

### v 0.7.2.1-b (2020-07-15)

#### Minor

- Added visible barriers to some unfinished sections
- Re-added turbo fast dialogue skip button (PgDn on KB / RB on controller)
- Added a secret tutorial for the dialogue skip button
- Update slot machine animations and sprite
- Added slot machine achievements
- Updated Fizz Boss sprite
    - Updated "Got U A Drank" achievement icon
- Added extra quest hints at Inner Tower
- Added extra dialogue to some NPCs at Sodatown
- Added dialogue when trying to give Soda to the Cleaning Man at Sodatown
- Added dialogue when trying to give regular weed to the stoner at Townsplace
- Changed some of the Straight Edgeland dialogue
- Changed a line at the Sodatown Museum
- Updated "Stoner's Weed" item name to "Spice", this was the intended name
- Reduced XP pay of Ninja Pirate (600 -> 350)
- Reduced DEF of Cleaning Man (12 -> 9), Greater Drunkard (10 -> 9)
- Increased SH pay of Cleaning Man (7 -> 12), Greater Drunkard (5 -> 12)
- Increased ATK and DEF of Loogie (ATK 5 -> 15, DEF 28 -> 38) 
- Increased DEF and MHP of A.P.E. (DEF 40 -> 50, MHP 4000 -> 5000)

#### Fixes

- Going from Route 10 -> Methropolis transported to wrong spot
- Ninja Pirates used outdated encounter events
- M.O.N.K.E.s used outdated encounter events
- Lab M.O.N.K.E. choice box was separated from its text box
- Really Funny Guy's portrait sprite was spilling into the white border
- Really Funny Guy disappears after being defeated
- Store Manager portrait was different from battle sprite
- Crack on lab exterior wall wasn't solid
- Sign at Soda Port had no dialogue
- Furby Trail didn't reset BGM from lab depths
- Route 10 and Furby Trail had no BGM
- Lab used missing sound
- A certain bossfight was reiniated after returning to its area
- Player gets stuck going from Cruise Hallway -> Cruise Room

#### Store

- Reworded some parts in the description
- Updated Overdose Edition feature list