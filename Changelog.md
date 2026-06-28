![banner image](https://raw.githubusercontent.com/sasquatch678/A-Painted-World---Remastered/refs/heads/main/Images/sunrise.png)

## **1.1.6/Revision 3**

**Added**
- Superior Sigil Stones
- Sigil Stones Effects - Magic Loader
- No Invisible World Border
- Marksman Fatigue Perk Rebalanced
- Oh Well
- Nosferat's Merchant and Loot Additions
- Alert Enemies
- Re-Evaluate Misc Item
- Ultimate Combat
- Amber Equipment Fix
- Auto Horse Pathing
- Black Robe Texture Fix
- Blades Gauntlets Fix
- Bound Armor Clipping Fix
- Darker Huntsman- Pants and Vest
- Darker Orcish Armor and Shield
- Forester - Darker Green Recolor
- HQ Secunda Earth Moon Retexture
- Less Cartoony Eating and Drinking SFX Replacer
- Shivering Isles Clothing Mesh Fixes
- Sitting camera fix (and race-list-based player height)
- ZZZ Red Diamond Jewelry
- Shiny and Glowing Skin
- Stop combat guard fix

**Updated**
- GSLoader
- Radiant Knights of the Nine Dungeon Quests
- Core Survival

**Removed**
- Ultra Combat V2 - Fixed Edition + Controller Config - redundant
- Protective Headgear - Daedric (Updated for 1.2)

**Changes**
- mcm is now opened with F12 to avoid another keybinding conflict
- added new reshade preset with a bit colder and more natural lighting - if you prefer the old one, you can toggle between them at any point ingame by pressing the PgUp key
- Ancestor Guardian uses slightly lower level fire spells
- renamed fire/frost/shock shield to fire/frost/shock cloak to make it more clear that these now deal aoe damage
- increased the barter and spell cost of fire/frost/shock cloak since they are a bit too efficient for 1 enchantment slot
- modified the text of 9 vanilla loading screens and added a few new ones to better explain changed and new mechanics
- added new ingame descriptions for racial abilities
- Roots of Valen woodelf passive no longer restores health or magicka, but now also fortifies 10 points of speed while outdoors
- rebalanced blackwater blade enchantment, no longer absorbs fatigue over time, but absorbs a greater amount on each strike - requires you to actively be hitting enemies instead of hit once and kite away until they fall down, repeat
- buffed fatigue of creatures to their vanilla values - for some reason the remaster reduces to 1/4 of their original value but doesn't nerf damage/drain fatigue effects to compensate so these spells just ragdoll everything within a few seconds

**Bugfixes**
- fixed issue causing Balanced Scales to constantly be added to dark elf players if they were below 50% fatigue
- fixed Jauffre having some lines referencing the Emperor's death before the MQ is started
- created file to hide "spell has been added to the player's spell list" for all scripted race effects
- fixed attribute descriptions in the levelup menu showing up as missing string entries

## **1.1.5**

**Added**
- GSLoader (UE5 Game Settings Loader)
- Denizens of Cyrodiil - All-in-One - also integrated with follower patch so these npcs can be recruited
- UE4SS Easy Tweaks
- Loot Glow
- Time on HUD
- AHP Cute Rats
- Blackwater Blade Fix
- Reworked Race Relations Remastered
- Disable Annoying Clipping Objects (Bliss Fountain plus Fort Linchal)
- The Necromancers Amulet Quest Fix
- Tempering Armor and Weapons - integrated with Smithing mod, added Smithing section to gameplay guide
- Better Origin Descriptions
- Spell Damage Scaling - UE4SS
- Pleasing Palettes - Dark Green Shirt
- Amelion's Paladin Armor (1.2 Updated)
- Daedric Quests - Fame Requirements
- Oblivion Music Legend - Chapter One - Echoes of the Past
- Faster Sleep and Wait - OBSE - conflicts with sleep system in Core Survival, added note to disable if using Core Survival

**Removed**
- Runtime EditorIDs (Console)
- Sha'dar - Panther Companion (Creature follower)
- Dynamic AI Behavior - Animals
- Core Survival Sound Addon
- True Bleed

**Updated**
- Core Survival

**Changes**
- the "Play" button now launches GSLoader, which in turn launches MagicLoader, which in turn launches OBSE. This does add about 10-15 seconds to the games boot time, but it also allows me to include modifications to game settings on the unreal side of things which previously was not possible without adding additional manual steps for you all.
- merged 46 plugins to make space for new additions as well as for people adding their own mods
- rebalanced difficulty settings to bring them each closer together and to utilize the full range of options. higher levels are actually playable - Master works out to be similar to the current Journeyman
- reduced damage of many creature enemies in the unleveled patch since these values were calibrated by the original mod author for a different set of rebalancing mods than what APWR uses
- increased player and horse movement speeds by ~10%
- reduced spellmaking and enchanting gold costs by ~15%
- increased swim speed in heavy armor by 15%
- the chance to recover arrows from corpses has been reduced to 50%
- there is no more delay to fatigue, magicka, or health regen
- passive health regen is reduced by 25%
- base magicka regen has been reduced by 25%, but the multiplier willpower has on the formula has been increased by 25% to make this attribute more attractive
- enemies will now suffer a slight knockback when hit with a melee weapon, increasing with your strength
- magic projectiles move 25% faster
- Restore Attribute can no longer be used in spellmaking or enchanting, and can no longer be purchased from spell vendors. With how powerful some birthsign lesser powers are, it doesn't make sense to allow the damaged attributes to be restored with a simple spell that can be infinitely recast. The intended gameplay loop is that you regularly visit chapels to restore attributes, or stock up on potions. You can also still use the greater power from the Lady Doomstone to fully restore all attributes once per day.
- intelligence now also scales your damage with spells and enchantments by 0.5% per level
- willpower now also increases your damage with staves by 0.5% per level
- Birthsigns which damage an attribute have had this damage increased to 3 per use (was 2)
- the Tower's passive damage reflection has been reduced to 10% (was 15%). The associated doomstone power has been reduced to 75% damage reflection (was 85%)
- Mage's Brilliance now Fortifies Intelligence by 100 points intead of Fortifying Magicka 250 points. This is to allow the power to now scale your spell damage instead of just adding to your available pool.
- Lover's Kiss now Calms any enemy for 10s, rather than 15 points of Charm for 15s.
- Ritual's Prayer now cures poison and disease, deals Holy Fire (fire+light) damage, turns the undead, and causes 25% weakness to fire over 10 seconds in a small area; no longer soul traps. The associated doomstone greater power now soul traps in an area in addition to its previous effects.
- Serpent's Bite now causes paralysis for 5 seconds. The associated doomstone power Star Curse now absorbs all attributes by 50 points for 120s and causes 500% weakness to poison on touch.
- Shadow's Prowl now also blinks the player to where the reticle is aimed.
- interacting with a Smithing Anvil will now give an option to temper your equipment, granting 10 points of Shield, Fortify Blade, Fortify Blunt, and Fortify Marksman for 15 minutes.
- the penalty to being detected while summoning daedra now only occurs after the kvatch oblivion gate has been closed, and to prevent cheesing the new daedric quest requirements it modifies disposition with the detecting npc instead of granting a point of infamy
- the Hunting Grounds for Hircine's daedric quest now play dungeon music instead of exploration music to better fit the atmosphere
- "Shield" sigil stones now grant more armor rating than their elemental shield counterparts, since elemental shields also grant resistance to that element and deal aoe damage
- removed mace and warhammer models from the practical arsenal series

**Bugfixes**
- fixed an issue causing wolves and some other animals to lose most of their aggression
- fixed the random coin clanking sound at the fountain in Mania
- removed detect life from Khajiit Prowl power to prevent bug which caused the purple detect life screen overlay to appear even when an npc cast the power
- fixed charm spells having a ridiculous magicka cost
- MCM is now opened with F10 to avoid a bug which could prevent closing the inventory

## **1.1.4**

**Added**
- Chillrend Remastered
- DB Quick Entrance Fix
- Turpentine - only 4 patches enabled, no more performance hit
- Sambuca's Creatures Overhaul - only the reach changes
- Less White Faded Wraith
- Advanced Followers Remastered - heavily tweaked

**Changes**
- reduced xp rewarded from lockpicking in Mad Experience
- removed war axes from the Practical Arsenal series
- headshots will no longer cause stagger, was too easy to perma stunlock enemies
- tier 1 blessings now include cure disease and restore attribute to make these effects more accessible with the birthsign system
- tier 3 blessings now fortify their respective attribute by 15 points (was 10) in addition to their other effects
- deluxe edition quest rumors can no longer be heard until the player completes Dagon Shrine

**Bugfixes**
- fixed all faction starts not adding needed dialogue topics that were required to proceed with the faction quests

## **1.1.3**

**Added**
- Blackwood Armour Redesign
- Mythic Dawn First Person Fix
- Optimized Tweaks OBLR
- Pointy Breton Ears
- Rabbit's Real Lights Imperial City
- Rabbit's Real Lights Skingrad
- Rabbit's Real Lights Bruma
- Rabbit's Real Lights Cheydinhal
- Altars for Temple of the One
- Alternate Start - Main Quest Delayer Enhancer
- ALTERNATIVE LEVELING - optional leveling method that forces you to use trainers to level up

**Removed**
- Classic Blackwood Company Armor
- Horses and Livestock
- TES4R Civis Sheep Wander Fix
- Ultimate Dialogue Overhaul - done trying to troubleshoot the ctds from this, the mod is broken simple as

**Updated**
- Sustaining Cyrodiil - A Farm Overhaul
- Melee Stagger UE4SS
- Race Based Runestones

**Changes**
- removed annoying initialization messages when starting a new game
- improved starting options - all starts will now be given 100 gold, 3 weak health/magicka/fatigue potions, food and drink, and more fitting equipment based on their skills
- decorated the starting room a bit so it's not so dark and empty
- removed "Guard" jobs from Jobs of Oblivion since there's a ton of overlap with Imperial Legion Infinitum, also they're kinda buggy from my experience
- lightly tweaked magicka cost scaling settings, with the goal to reduce how big the scaling cost reduction can get at endgame
- slightly buffed movement speed with shields and when a weapon is drawn
- alternate start is no longer in optional section since it requires some records to be forwarded into the conflict resolution patch. You will play the tutorial anyway when you start the main quest.

## **1.1.2**

**Added**
- Fancy Tan Robe
- Cataclysm Armor Fixes
- Tinted Glass Armour and Weapons
- Blackwood Company Wears Blackwood Armor
- Alternative shock spell icon
- HQ Masser Blood Moon Retexture
- Vampire Feed Bug Fix
- Kynareth's Grotto Restored
- Skeleton's Bane
- Masquerade (Faction Disguises) - only guard uniforms
- Rebalanced Weakness Enchantments
- Silent Torch Equip SFX - helps with the random torch equip sound bug
- Alternate Start - Main Quest Delayer
- Mad Experience - Alternate Leveling System - both static and non-static versions to optional section - pick one, or neither if you like vanilla leveling
- Radiant Mages Guild Dungeon Quests
- Radiant Knights of the Nine Dungeon Quests
- Vampires' Conditional Sun Damage
- TES Legends Classic loading screens - Remastered

**Removed**
- Not so deadly trap
- Lethal Lava
- Simple Fast Start - Adventurer's Inventory
- Enhanced Tree Bark - causes weird glossy trees in blackwood
- TES4R Civis Daedric Quests Fix
- Remastered Loading Screens

**Updated**
- Knights of the Nine - Infinitum
- Daedra Are Actually Bad
- Daedric Might - Daedric Artifacts Overhaul
- Reshade

**Changes**
- increased the base cost of Calm and Invisibility spells by 2x - it was really easy to cheese enemies with these effects
- greatly reduced the reach of Large Mudcrabs
- greatly reduced the reach of goblins
- Burden effect on Tower's Vigilance now lasts the same duration as the buff
- increased ability of actors to detect the player when the player is already in combat
- reduced the purpleness of foggy weather

**Bugfixes**
- fixed several more inconsistencies with leveled lists and creature spawns when playing without the unleveled patch
- "Trade With Clavicus Vile" is no longer considered a starting conjuration spell
- fixed ctd caused by all daedra summoning spells
- added AltVoiceFaction (used to trigger the new voice acting in the remaster) to npcs of applicable races in every mod that adds new npcs, since every single one was missing this - could cause ctd when approaching these npcs in combination with Ultimate Dialogue Overhaul
- fixed gas traps not dealing any damage


## **1.1.1**

**Added**
- Daedric Claymore Glitch Fix
- Better Oblivion Crisis - Greymarch Edition
- Vampire Hunting - Infinitum
- Imperial Legion - Infinitum - modified quest so it only begins after the player completes the quest "Imperial Corruption" rather than immediately on game start
- Initial Quest Popups Begone
- Mastercrafted Steel Armor - Remastered
- Blue Axe of Icy Darkness
- Alternative Quest Icon Colours
- Skingrad East Stable Clutter
- Major Minor Mediation
- Iron Palm - Hand to Hand Rebalanced
- Simple Leather Eyepatch (UPDATED FOR OBR 1.2)
- Enhanced Tree Bark
- Unarmed Equipment Expansion
- Oh Deer
- Scabbards Of Oblivion (SOO)
- Reduced Screen Blood Splatter
- Linked Chests - Shared Storage for Player Homes
- Reworked Race Heights
- Arcane University Player Room
- Cloud Ruler Temple Player Room
- Hoe_Rake Anim Glitch Fix
- Quarantined Oblivion Gates
- A Kvatch Survivor
- The Breton Hero Armor
- Sheogorath's Beard
- Magical Item and Spell Sorter (MISS) - Customisable Inventory Sorting (optional section)
- Swift Claymore
- Female Locomotion Replacer v2 (Crash Fix)
- Sambuca's Armors Overhaul - not the spell effectiveness changes
- Daedric Might - Daedric Artifacts Overhaul
- Gold to Septims
- Melee Stagger UE4SS
- Knights of the Nine - Infinitum
- Reduced Climbing Penalty

**Updated**
- Infinitum - Compendium
- Core Survival

**Changes**
- increased movement speed in heavy armor slightly
- reduced movement while moving backwards and strafing, primarily to make marksman players less invincible
- tweaked sneak game settings to make sound and running a higher multiplier in the overall formula
- restore magicka can no longer be used in custom spells or enchantments
- restore health and fatigue can no longer be used in custom enchantments
- paralyze can no longer be used in custom enchantments
- reworked formula for soulgems, and custom enchantments and spells. the gold cost to make custom spells/enchantments now scales less with intelligence, but the system is actually useable with a normal amount of charge now (woops). Additionally, soulgems will no longer recharge for a pitiful amount.
- small mudcrabs are now much less aggressive, practically docile. Larger mudcrabs are also a bit less aggressive
- doubled the value of daedric weapons - with the modified rarity, the original values in Sambuca's Combat Calibration don't make sense to keep
- increased reach of two-handed weapons by ~20%
- changes to the unleveled patch to make the creature variety added by ORWO more common
- ayleid wells now also restore magicka 1/s for 5 minutes in addition to their existing effects, to give a reason to continue interacting with them even after collecting their one time fortify magicka buff
- ayleid wells no longer restore hp as this just incentivized kiting difficult enemies to wells to get a onetime use full heal during the fight

**Bugfixes**
- reverted change made by TES4R Civis Master Trainers Fix to modify the GameHour variable to be a float rather than short value. This was causing a specific crash and could have also been reponsible for other odd behavior. There is no reason this mod should be changing this variable in this way, nor any mod for that matter.
- removed AI packages added by TES4R Civis Sheep Wander Fix as these could cause the game to crash - another unnecessary change for what the mod is meant to do
- may no longer hear rumors about the deluxe edition quests while in the Shivering Isles
- fixed several inconsistencies when the unleveled patch was toggled off
- fixed an issue that prevented flame atronachs from casting spells
- applied "Fix and Port Script" to all mods in the load order - this fixed over a dozen plugins with bad cell data and missing location tags that are unique to the remaster
- fixed the Blue Team Gladiator in the Bloodworks deciding they don't need to wear anything at all

## **1.1.0**

**Added**
- AI Actor limit fix and Longer Corpse Despawn
- Being A Vampire Makes People Dislike You
- Quicker Quill-Weave - Alternative Solutions for Fighters Guild Rat Problem Quest
- Sha'dar - Panther Companion (Creature follower)
- Simple Dog Follower - Clancy
- Sigil Stone Transmuter - Varla Stone Cost
- The Glarthir Dilemma
- Bathhouses of Cyrodiil
- Guards Revised
- Ultimate Dialogue Overhaul - found conflicting mod that caused it to crash in the past, and it's being removed now
- Realistic Combat Behaviour
- Fatigue Affects Damage - doesn't have issue where attacks could deal 0 damage anymore
- Balanced Shield Bash
- Still NPCs - Less Head Movement
- Wrathplate Armor Overhaul - distributed as a unique armor set to the Knights of the Thorn
- Static Loot and World - Oblivion Overhaul
- TWEAKS for Static Loot and World

**Updated**
- MO2 to latest dev build, which allows plugins to be sorted above the Altar plugins. The hope is that this will fix issues with TesSyncMap for users who don't own the deluxe edition of the game

**Removed**
- GSR Stealth Crime n Thievery - causes crashes with Ultimate Dialogue Overhaul (something to do with guards)
- Better Sneak - implemented what can be (which is most of the mod) via esp to reduce reliance on ue4ss
- Unique Artifacts - Sinweaver - Replacer - not updated to 1.2 so causes the game to ctd

**Changes**
- merchants now sometimes sell enchanted arrows instead of only regular arrows
- reverted previous change to the Atronach sign to deal aoe elemental damage as the constant spam of the effect in combat was really annoying, now it just grants elemental and physical resistance again
- spirit hounds and revenant enemies now have standard ethereal undead resistances, like you would expect from ghost-like enemies
- undead with "flesh" resistances now also restore 1 point of health per second
- reworked Stendarr and Arkay's blessings since they had some overlap with one fortifying health (doesn't even work in the remaster lol) and the other fortifying endurance. Stendarr now fortifies armor rating, while Arkay fortifies Endurance along with their other progressive bonuses based on devotion.
- decreased slow-mo duration and magnitude for various combat actions to 1s (was 2s)
- mythic dawn robes are no longer enchanted with fire shield
- increased duration of buff given by donating to a beggar to 120s (was 60s)
- moved Wear Robes With Boots Gloves Greaves to optional mods section
- slightly reduced black levels as nights and some interiors were darker than intended
- removed ability to contract blight diseases - these are just annoying
- reduced headshot damage by 50%
- nerfed the damage and enchantments on weapons added by Vampire A Cursed Arsenal to a much more reasonable level (they were all as powerful as daedric equivalents with almost infinite charge)

**Bugfixes**
- fixed bug preventing power attacks from being triggered on controller
- skeletons can no longer bleed

## **1.0.17**

**Added**
- Ultra Combat V2 - Fixed Edition
- Grass Replacer - WildGrass 2.0

**Updated**
- Core Survival Sound Addon
- Oblivion Travelers
- More Immersive Daedra Worshippers Redux

**Removed**
- Ultra Combat
- True Fatigue - Stamina Management Overhaul
- SM Combat Hide
- Turpentine

**Changes**
- Ultra Plus is now enabled by default - with Ultra Combat - Fixed Edition this no longer seems to crash when starting a new game

## **1.0.16**

**Added**
- Grass Replacer - Cattail 2.1

**Updated**
- Glorious Holes of Oblivion (GHO)
- Map Experience Overhaul
- Brazier Meets Wood (BMW)

**Removed**
- Natural Bodies and all addons/dependencies for it - unstable and too many clipping issues
- Practical Arsenal - uniques - was not properly updated for 1.2, still crashes the game
- Lived In - Imperial Waterfront - simply way too heavy on fps

**Changes**
- Khajiit Stalk passive now grants movement speed while sneaking instead of Chameleon, renamed to Feline Grace
- removed controller profile, added controller config for Ultra Combat to optional section instead
- Quick Cast (Cast Automatically) moved to optional mods
- Mythic Dawn now use leveled fire spells instead of shock spells
- removed the random unowned horse you could just take for free on the Talos Bridge
- removed Dispel on touch from the Lover lesser power as this made the npc you use it on hostile if used for purposes of the charm effect
- increased amount of each attribute absorbed by the Serpent lesser power to 25 (was 15)
- Atronach passive now grants 5 points of each elemental shield to make use of Supreme Magicka's change to make these effects deal damage in an area around you (was 15 points of resistance to each element and 15 points of Shield)

**Bugfixes**
- fixed issue that could cause player to get stuck in the air when pressing jump

## **1.0.14**

**Added**
- Immersive Movement
- Sustaining Cyrodiil - A Farm Overhaul
- Idle Dialogue Remaster
- Supreme Magicka - Extrication Spell Freeze Fix
- Vampirism Eye Fix
- TES4R Civis Deluxe Content Fix
- Map Experience Overhaul
- Basin of Renewal Crash Fix
- True Fatigue - Stamina Management Overhaul
- True Bleed - A Damage Over Time Bleeding Overhaul
- Dynamic Difficulty Multipliers (MCM) - default settings make Master 4x damage taken 25% damage dealt (vanilla is 6x damage taken 16.7% damage dealt)

**Removed**
- Little Quests
- Eyebrow Retexture
- Analog Controller Speed and remove Inertia - Gliding (UE4SS)
- Amelion's Paladin Armor - sword ctds
- Ultimate Dialogue Overhaul - many ctds tied to this mod
- NPCs Catch Fire
- Faster Mountain Slope Climbing - conflicts and redundant with Immersive Movement

**Changes**
- enchanting magnitudes now have an intelligence cap to prevent a fortify intelligence loop
- removed insane fortify health passives added by Stronger Bosses
- added a separate controller profile - currently this only does two things, changes the dodge button to B (or O) and disables one button power attacks

## **1.0.13**
**Added**
- Hides His Heart Voice Fix
- Underwater Treasures
- Sensible Shields - Daedric
- Protective Headgear - Glass
- Protective Headgear - Amber
- Protective Headgear - Elven
- Sensible Shields - Iron
- Practical Duskfang and Dawnfang
- Practical Order of Jyggalag
- Sensible Shields - Leather
- Sensible Shields - Knights of the Thorn
- Sensible Shields - Elven
- Practical Uniques

**Updated**
- Ultimate Dialogue Overhaul
- Harrada Spiddal Plants Dart Traps Fix
- Jobs of Oblivion
- More Immersive Daedra Worshippers
- Nirnroots Glow Fix

## **1.0.12**

**Added**
- Castle Brazier Fix
- CRT West Wing Door Fix
- TES4R Civis Ascended Immortals Spawn Fix
- Simple Fast Start - Adventurer's Inventory

**Updated**
- TES4R Civis Sheep Wander Fix
- Ultimate Dialogue Overhaul

**Removed**
- Simple Player Eating Idle - the Core Survival version is outdated

**Changes**
- reverted Jewel of the Rumare enchantment effect to waterbreathing instead of waterwalking
- Core Survival moved to optional section (disabled by default), removed my custom script edits as they were breaking the mod in some places

## **1.0.11**

**Added**
- Amelion's Paladin Armor (1.2 Updated)
- Protective Headgear - Leather (1.2 Updated)
- Protective Headgear - Crusader (1.2 Updated)
- Protective Headgear - Glass Helmet (1.2 Updated)
- Practical Arsenal - Glass (1.2 Updated)
- More Immersive Daedra Worshippers Redux
- Injuries

**Updated**
- Arena Armor Overhaul (WIP)
- Core Survival
- Ultimate Dialogue Overhaul
- Dark Brotherhood Arsenal ReDone (WIP)

**Removed**
- Faster Sleep and Wait - conflicts with sleep system
- Fatigue Affects Damage - strange behavior on higher difficulties (enemies healing/taking no damage)
- Engaging Combat - redundant with Injuries, which I think is a better system

**Changes**
- negative survival effects reworded for clarity/immersion

## **1.0.10**

**Added**
- Pleasing Palettes - Red Silk Hood and Robe
- Honorable Arena
- Two Sides of the Coin Quest Tweaks
- Spell Tomes DLC - Tweaks and Fixes
- Jobs of Oblivion
- Better Sneak

**Removed**
- Unlocked Arena - causes some weird bugs, and I think it gives too much freedom. Implemented my own version with Honorable Arena that just allows you to loot enemies in the arena, but doing so adds a point of infamy (also plays the crowd boo sound, immersive!).

**Changes**
- nerfed Arena equipment enchantments and reduced gold value so they can't be exploited for huge gold
- hypothermia and hygiene system are enabled by default (requires new game to take effect)

**Bugfixes**
- fixed Owyn wandering around the Bloodworks which could soft-lock the player if they spoke to him from the other side of the gate after a match as the gate would close immediately after
- consistency patched elven waraxes and enchanted variants to the same speed
- fixed nude body option not working
- removed thigh and butt physics on male body presets

## **1.0.9**

**Added**
- Dynamic Magic Crafting
- Classic Blackwood Company Armor
- Less Bulky Iron Armor
- Less Bulky Fur Armor
- HD Reworked Leather Armor
- HD Reworked Ebony Armor
- Natural Bodies of Oblivion (NBO) with Body Morph - (nevernude enabled by default)
- Natural Male Bodies - NBO Addon - (nevernude enabled by default)
- Race-based Player Body and NPC Bodies for NBO
- NBO - Outfit Conversion - All-in-One
- NBO and NPCAM Stability Patch
- Labelled Skill Books

**Changes**
- slightly reduced boar attack damage
- slaughterfish are more aggressive and a bit faster
- Ultra Plus moved to optional section and disabled by default for a better new user experience

**Bugfixes**
- fixed minor clipping with the statue plaques in the Arboretum
- fixed vilverin bandits having a negative level offset which could result in infinite hp if the player was low level
- fixed UW hud options missing from install

## **1.0.8**

**Added**
- Statues of Cyrodiil
- Little Locations
- Little Quests
- Tribal Minotaur Camps
- Vampires Cursed Arsenal
- Sinweaver Replacer
- Hircine Quest Expansion
- Lived In - Arcane University
- Lived In - Imperial Waterfront - tweaked to improve fps
- Lived In - Imperial Gateway - tweaked to improve fps
- Lived In - Imperial Docks - tweaked to improve fps
- Realistic High Quality Skin
- Young Textures Revamped
- Indoril Odyssey
- Urban Bypass - Alternative City Entrances and Exits
- Mages Guild (Remastered)
- Oblivion Travelers
- Smithing
- More Natural Elf Male Head
- More Natural Elf Female Head
- Nerfed Damage Enchantments
- Devastation of Kvatch Redux Remastered
- Balanced NPC Level Cap
- Simple Creature Level Cap
- Faster Sleep Wait
- Better City Gate Sound FX
- Wooden Door SFX

**Removed**
- Better Dialogue - I would rather have paused dialogue menus than deal with npcs moving while you talk to them every other conversation. Also potentially causes issues with scheduling since time is not truly paused.
- Aldos Othran VA Restored
- Beast Voice Variety
- Shivering Isles Voice Acting Restored - the way these mods are implemented causes the affected npcs to lose their lip sync

**Updated**
- Guild Advancement
- Core Survival (Needs - Cooking - Fishing)

**Changes**
- weapons will now recharge 50% of their charge per day (was 3,200 points per day) to not totally invalidate soul gems
- reduced amount of mudcrab spawns in leveled lists
- increased slope climbing speed
- no longer need to sleep to level up, it just happens automatically
- nerfed enchantments on dark brotherhood equipment
- spellmaking and enchanting altars in the mages guildhalls will now use the frostcrag altar model to look a bit more official, like they are officially sanctioned by the arcane university
- increased gold cost to enchant items significantly
- arena raiment now adds 50% resistance to paralysis, and the raiment of valor adds 100% resistance
- arena combatants now all have 100 sneak and passive night eye, so they can more easily detect if the player is trying to sneak back in one of the hallways
- nerfed damage of trophy boars
- added ores from Smithing to blacksmith leveled lists

**Bugfixes**
- fixed several more clipping conflicts in the Anvil and Chorrol Mages Guild
- fixed several clipping conflicts and small issues in the Cheydinhal Sanctuary
- fixed Land Dreugh being unable to attack

## **1.0.7**

**Added**
- Sketchy Merchants
- GSR Stealth Crime n Thievery
- Gamblers of Cyrodiil
- Yami's Conjuration Rebalanced
- Yami's Lore Friendly Daedric Artifacts
- More Unique look for Unique Daedric Realms
- Sambuca's Weapons Overhaul
- Sambuca's Badass Enemies
- Immersive Quest Marker Overhaul

**Updated**
- Let's Eat - Core Survival Version

**Removed**
- Responsive Combat AI - redundant

**Changes**
- enabled health regen by default
- further reduced necromancer and mythic dawn enchantments to lower the sell value
- Trophy Boars and Bucks will now drop a higher value hide than their regular counterparts + fixed AI for Trophy Bucks to run away now
- Mudcrab Chitin and Rat Pelts no longer have Cure Disease as their first alchemical property as this created an extremely easy way to get rid of diseases. Instead Chitin now has waterwalking and Rat Pelts have Resist Disease as the first property
- Skeleton key now fortifies luck by 10 instead of sneak by 25
- reworked Divine blessing tiers, see [Gods and Worship](https://github.com/sasquatch678/A-Painted-World---Remastered/blob/main/Gameplay/Miscellaneous.md) for details
- reduced scale of giant slaughterfish, and the amount of items in its inventory
- reduced attack reach of all mudcrab variants and skeletons
- disabled spell burn by default as I find getting hit by a spell generally punishing enough without it

**Bugfixes**
- fixed issues with the arena raiment
- fixed the emperor's entourage getting stuck at the door during the tutorial where the wall breaks open with rats

## **1.0.6**

**Added**
- Beneficial Enchantment Glow Begone
- TES4R Civis Sheep Wander Fix
- Noble Horse Armour - Steel Horse Armour Retexture
- Reduced Procedural Slope Leaning
- Better Reticle
- Devotion - Blessings Remastered
- Dark Brotherhood Sanctuary Player Room
- Dangerous Waters
- Quick Cast (Cast Automatically)
- No Vignettes
- SM Combat Hide

**Updated**
- Ultimate Dialogue Overhaul
- Core Survival

**Removed**
- Mad Spell Pack - LUA Magic Effects - UE4SS - just doesn't fit into the list very well and causes black screen issue/crashes
- Mad Mod Config Menu - it can apparently cause some crashes on load and there just isn't a great reason to keep it
- Rebalanced Movement - Slower Run and Sprint - redundant and could have a conflicting hook with Analog Controller Speed and remove Inertia - Gliding (UE4SS)

**Changes**
- made Imperial Palace Guard armor playable
- made sunrises a bit less purple
- nerfed run and sprint speeds to a reasonable level

**Bugfixes**
- downgraded Wonger's Shield on Back to 0.3 to avoid ctd issues

## **1.0.5**

**Added**
- Arborwatch interior renovation
- Waterfront Shack interior renovation
- Cheydinhal House interior improvement
- Miaura's Dunbarrow Cove Enchanted
- Immersive Player Homes - Deepscorn Hollow
- Unique Elemental Spells
- Unread Skill Books Glow
- ORWO - Ghosts and Spirits
- Vile Lair DLC - Tweaks and Fixes
- Benirus Minor Makeover
- Practical Arsenal - Fine Steel
- Protective Headwear - Guard
- Protective Headgear - Steel Closed Helmet
- Protective Headgear - Iron
- Portals to Hell
- Knights of the White Stallion Armor
- Another Lock Retexture
- Thieves Guild Hoods
- Hooded Outlaws
- No Starting Spells
- Original Font (Kingthings Petrock)
- Mages Wear Robes (Mages Guild Outfit Overhaul)
- Two-handed Weapons Reach and Damage Increased
- IRON ARMOR - BATTLEWORN RETEXTURE
- Enemy's Weapon Stays on Corpse
- Faster Mountain Slope Climbing

**Removed**
- Eli's Waterfront Shack Overhaul - causing crashes
- Leyawiin Home Overhaul - invalidates home upgrade system
- No Player Health Regen - can be added via Altar.ini instead, better to avoid UE4SS where possible

**Changes**
- Rebalanced robe enchantments (again). Only Mythic Dawn, Necromancer, and Mages, Apprentice, and Conjurer robes have enchantments now.
- High elf Highborn power now restores magicka over 60 seconds instead of fortifying intelligence and dispel. The Reman upgrade now adds spell absorb instead of spell reflect, and the Sidri upgrade is now the only one with the dispel.
- Khajiit no longer have Eye of Night as a bonus lesser power, instead the effects are baked into Prowl
- Nord Sidri and Hestra effects have been swapped
- Orc Stormrunner passive now grants 15% magic resistance and 25% resistance to shock (was just 50% shock resistance)
- Breton magic resist is now spell absorb. Reman upgrade now also adds 50% spell reflect. Sidri upgrade now grants 75 Chameleon
- the skeleton key now fortifies sneak by 25 points, rather than a borderline useless 40 points of security
- greatly reduced the amount of junk you start with when using the alternate start mod

**Bugfixes**
- fixed equipment not degrading by default
- fixed some clipping conflicts between Infinitum Compendium and Available Arcane Enchanters

## **1.0.4**

**Added**
- Ultimate Dialogue Overhaul

**Updated**
- Core Survival
- Core Survival SFX Addon

**Removed**
- Backpacks of Cyrodiil - causing crashes
- Mad OBScript Extender - redundant
- Close Menus - causing crashes
- Spell & Arrow Stagger Chance - causing crashes
- Map Experience Overhaul - causing crashes
- Dynamic Multiple Summons - causing crashes
- Statues of Cyrodiil - causing crashes

**Changes**
- rebalanced robe enchantments

**Bugfixes**
- fixed bug that could cause a low level character to deal 0 damage when playing on a high difficulty setting

## **1.0.3**

**Added**
- TesSyncMap
- MagicLoader2
- Armored Legion Horses
- No Player Health Regen (optional)
- Wayshrines - Quaint addon (non SyncMap version)
- Pell's Gate - Quaint addon
- Inns - Quaint addon
- Quaint Roads - More Road Signs
- Constant Orrery Effects
- Daedra Are Actually Bad
- Better Oblivion Crisis - Cultists Replace Conjurers
- Roadside Grass to Little Weeds
- Vamped Up Vampires
- Infinitum Compendium
- Unseelium's Sufferthorn - Standalone
- Dark Brotherhood Arsenal ReDone
- Arena Armor Overhaul
- Backpacks of Cyrodiil
- Robes Plus - Mage Arsenal
- Diverse Staves
- Enhanced Goblin Wars
- Faction Home Improvements
- Mythic Dawn Rising
- Statues of Cyrodiil
- Stronger Bosses
- The True Staff of Mannimarco
- Core Survival
- Core Survival SFX addon
- Let's Eat - Core Survival version
- Core Survival Simple Hunting Overhaul Patch
- Core Survival TesSyncMap Patch

**Updated**
- Reshade to latest version

**Changes**
- added Telekinesis script from Supreme Magicka to Thief's Spree, so you can use it to blink/teleport
- altar blessings now last for 1800s (was 300) and wayshrines last for 3600s (was 600)
- changed major skills for Knight, Warrior, Barbarian, Crusader, Archer, and Battlemage to not have more than one weapon skill so they aren't so useless
- slightly improved color grading
- removed unused reshade shaders for quicker shader compiling

**Bugfixes**
- fixed missing string table entry for khajiit stalk passive, and ayleid well, rune stone, and obelisk of order map markers
- fixed shadow's prowl lesser power causing the player to stay (visually) permanently invisible by removing the chameleon effect
- fixed lighting/fog bug that could appear in the following cells: Fort Farragut, Fort Sutch, Cheydinhal Sanctuary, Battlehorn Castle Master Bedroom, and the Archmage's Lobby
- fixed some mudcrabs moving extremely quickly
- fixed several "Trophy" creatures which could drop duplicate versions of pelts/fat/meat/ingredients that did not stack
- fixed conflicts with Quest Journal Directions and Battlehorn Castle Expanded
- fixed altars not restoring an attribute
- fixed being unable to buy gardens for player homes

## **1.0.2**

**Removed**
- MagicLoader and every mod that was dependent on it
- TesSyncMap and every mod that was dependent on it
- NPC Appearance Manager and every mod that was dependent on it
- RaceMenu Utilities

## **1.0.1**

**Removed**
- Skip Intro Screens - apparently it can sometimes cause issues launching the game
- Alternative Intro Main Menu
- Kwa Stacking Notifications - incompatible with Notification Watchdog

**Bugfixes**
- fixed Reshade not initializing correctly
- fixed being unable to use spacebar to skip/close menus
