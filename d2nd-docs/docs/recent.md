# Recent patch changes

<!--

## 1.2.1
Fixes the following:

- game now works with vanilla version 2.7
- more than 600 minor bug fixes and performance improvements! (Thanks, D2RLint!)
- fixed a nasty property duplicate bug that rendered wrong properties
- skill tree panels now reflect correct prereqs for skills (dependencies simplified)
- removed Might from Holy Fire requirement
- removed Amplify Damage from Weaken requirement
- skeletal mages now correctly spawns with fire and lightning mages exclusively
- Essences (burning, festering, hatred, etc) now unstack into unstacked versions
- correct skill tabs are now infused from Blood Biddings
*- reduced distance for Force Cleave missile 
*- all poison-based attacks and properties now have a global 3 second duration
- + elemental skills now properly give their bonuses
- Decrepify now properly reduces speed, attack rate AND cast rate (casters beware in Chaos Sanctuary)

Balances the following
- renamed Skill Biddings to "Blood Biddings" and can only be infused into Sunder Charms
- Enigma's Teleport are now "Lesser Teleport" with a long cooldown
- Demon Machine now spawns with ctc Firewall
- renamed all biddings to generic "biddings" so player is forced to pick up


Adds the following:
*- Slabs of Faith now drops from certain superuniques from Nightmare difficulty 
*- Gheeds Gambles now drop from Terrorized uniques and Champions
*- chipped, flawed and normal gems now drop from superuniques in Nightmare difficulty
*- chipped, flawed and normal gems can now be used to build different Crafting Stones
*- Crafting Stones can be partly built by transmuting 50 Jewels (stacked) and a Crafting Stone. To finish a Crafting Stone you have to transmute infuse 50 runes (stacked) and 50 P Gems (Stacked) that can be used to craft new items directly 
*- edited Crafting recipes to only use runes 1-7 for all crafting types
*- enabled a recipe to build Obsidian Stones (Flawless and Perfect) to use for Slabs of Faith and Sunder Charms
- Sunder charm biddings now drop from Hell Terrorized zones and can be used to craft Sunder Charms
- new automod "% to not consume charges" added to all claws, daggers, bucklers, small shield and large shields, and random automod for gloves

Assassin:

- elemental Charge Up skills now incur a linear resistance penalty (minus resistance and minus max resistance)
- removed dependencies between Elemental Charge Up skills
*- If more than one Elemental Charge skill has points in it, a global 10 second cooldown will be set to all Elemental Charge Up skills. Phoenix Strike is the exception and this will encourage the player to pick a single element to focus on (while still being able to use different PS charges for dual elements)
- Shadow Master is now a physical finishing move called "Shadow Chaos Stab" that can be used only with a dagger 
- Cobra Strike charge 1 now is a poison Cloud and charge 3 is an AoE poison-based attack
- Cobra Strike now has progressive stack when charges are released
- Phoenix Strike now has a flat "minus magic damage reduction" penalty
- reduced PS charge 3 Chaos Ice freeze significantly 
- Tiger Strike now has a flat "minus physical damage reduction" penalty 
- Dragon Talon now has a maximum of 1 kick no matter the skill level (due to crazy unbalance when using Mosaic)
- all Finishing moves (with the exception of Dragon Flight) now no longer always hits

Druid:
*- add teleport skill (Frost Wind) instead of "Frozen Inferno"
*- add ctc firestorm to Fireclaw attack
*- add bonuses to "Mark of Bear/Wolf" to Werebear and Werewolf skill
*- Shockwave now splits into multiple waves when more skills are put into it and increases stun length
*- Multiple Vines can now be spawned 
*- Spirit of Barbs now does something else entirely to make it more useful
*- Cooldowns removed from most elemental attacks
*- Ravens now deal cold damage
*- Bean and Wolf Summons now synergise with Werebear and Werewolf (pack leader, GO!)

-->

## v1.2.0 - Pets and Peeves

Fixes the following:

- Corrupting rings with life after kill now correctly adds life after kill attribute
- Amazon javelins and bows, and Sorc Orbs now spawn with their correct automods
- Barb Battle Cry now correctly decreases enemy physical resistance (can also break immunities)
- more fixes for weapon splashing

Adding:

- support for patch 2.6
- support for Terror Zones

Sorc:

- Meteor and Firewall can now be cast continuously on controller

Paladin:

- Holy Bolt no longer pierces

Barb:

- removed Stun
- removed Concentrate
- added new lvl 12 skill: Great Cleave. Two-handed weapons only (not swords). Strikes a piercing wave through enemies on attack. 
- added new lvl 18 skill: Cleave. 1-handed weapons only. Casts melee splash damage that arcs to multiple enemies close nearby.

Necromancer:

- complete revamp and balance of all skill trees, curses are enhanced, golems are now viable, and bone and poison skills all have their own niches 
- see Change log for full changes

## v1.1.0 - A Song of Ice and Fire: Electric Buggaloo

Fixes the following:

- Fixed all issues with missing splash damage on weapons
- Defiance aura now actually provides 1% DR per 2 base points (also includes Act2 Defiance Merc)

Adding:

- strafe now synergises with magic arrow
- guided arrow now synergises with magic arrow
- inner sight now provides -% to enemy AC
- penetrate no longer provides -% to enemy AC
- strafe is now for bows only
- multiple shot is now for xbows only 
- multiple shot now provides crushing blow
- magic arrow: magic damage base conversion reduced, synergy added to guided arrow, synergy added to multiple shot
- increased damage to multiple shot
- removed some affixes from rare bolts and arrows so they only spawn on magic bolts and arrows

Paladin and Sorceress skill changes:

- see change log for details

## v1.0.3

Fixes for the following issues:

- Pruby and Psapphire cubing swallows other items
- Experimental fix for crash twice (skilltab biddings id corrected)
- Uber keys stacks no graphics
- Fomenters crafted ring now requires Tal rune
- Charges now have rare items in the description for forging
- Teleport charges now show on Spellsteel
- Typo in Elemental Bidding text
- Shield corruptions no longer returns flawless on bricking
- Synergy description bug for Find Item
- Fixed string bug for Deadly strike suffix

Added:

- Backend structural changes that allows for easier handling of future Blizzard updates
- Iratha's full set bonus now decreased
- Description for flawless gems transmuting
- New names for biddings and infusion points (Biddings of Li-Ming and Spirit Infusion)
- Decrease Power Strike cost
- Lightning Fury bolts now caps at 11 and scales with the number of skill points
- Increase Hell bidding drops
- Full rejuvs now only heals 65%
- Essences (Twisted, Suffering, Hatred) now drops in Hell difficulty (instead of full tokens)
- Token of Absolution stacks now unstack into unstacked tokens 
- Decrease mana cost for Leap and Leap Attack

## v1.0.2

Fixes for the following issues:

- Flawless gems transmuting to Perfect
- Forging anything but set weapons and armor failed

## v1.0.1

Minor update with fixes for:

- Rune stacks, orbs, essences, charges, new stacks now shows on ground
- Unlimited unstacking of most rune stacks
- Weird light rays underground
- No roof on Travincal temple
- Corruption color overflow for corrupted set items
- No longer corruptions with no new attributes
- Act 5 merc suiciding and crashing the game

Added:
- Descriptions on Flawless gems explaining that they can be transmuted into other flawless gems
- Save folder with enabled additional shared stash tabs
