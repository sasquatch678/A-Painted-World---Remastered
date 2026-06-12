![banner image](https://raw.githubusercontent.com/sasquatch678/A-Painted-World---Remastered/refs/heads/main/Images/magealchemy.png)
# <p align="center"> MAGIC

Magic has received a light overhaul to better the leveling experience, and add variety to some of the more niche spell effects. There are some general changes to spellcasting and magic related systems below.

- **Staves** now have a script that adds magicka bonuses while equipped﻿. You will gain a Magicka Multiplier equal to (10+ 0.5 + 1.25 x Intelligence x 0.025). Theorethically you could get thousands of spell points if your intelligence is over the roof. You will also gain a bonus to your magicka regeneration while holding a staff, starting at 1/s at 50 Willpower and scaling up to 5/s every 25 points of Willpower, up to 125.

- **Robes** no longer take up the lower clothing slot, so you can use an extra enchantment slot on your leg equipment with a robe. 
>[!TIP]
>This can create some clipping, but can be easily toggled off by disabling the mod in the optional mods section of MO2.

## <p align="center"> Magic Skill Leveling Changes

### Spell Cost Based XP
Oblivion Remastered added a new XP gain system for Magic skills. Sadly they based the XP gain on the base cost of spells. Oblivion's high tier spells have incredibly high base costs, while compensating for that with an aggressive spell cost discount from high Magic Skill levels. By adding XP gain on the base cost of spells, the Oblivion Remastered devs introduced a major imbalance, causing Magic Skill leveling to accelerate the closer the skill level gets to 100.

This imbalance is fixed by making the XP gain proportional to the actual spell cost (the amount displayed in your Spell Book; the amount subtracted from your Magicka pool). This brings the leveling speed of Magic skills in line with non-Magic skills.

### Flat per-cast XP
Strangely enough, the Oblivion Remastered devs left the original Oblivion magic skill XP gain system in place, so there are two XP systems now. The Oldblivion system gives a flat amount of XP-per-spell-cast, regardless of spell cost. The main problem with leaving this system in place in Remastered, is that the Oldblivion devs chose very high flat XP values for magic schools with generally expensive spells, like Conjuration, while giving very little flat XP-per-cast to schools featuring low cost spells that are generally spammed by the player, like Minor Healing or Flare for Restoration and Destruction.

This made a lot of sense in Oldblivion, but with the addition of the cost-based system of Remastered this discrepancy in flat XP gain between schools has no justification anymore. This is also fixed by giving NO flat XP-per-cast.

## <p align="center">  Magic School Changes

### <p align="center"> DESTRUCTION
#### Elemental Damage
To improve the effectiveness of standard frost and spark spells/scrolls (not custom spells) they now include additional effects, inspired by Skyrim. Frost spells cause additional fatigue damage, shock spells cause additional magicka damage, and fire spells deal bonus damage over time. Beware as these effects can affect you too from enemies. A journeyman of destruction will cause fire and shock spells with a duration to blast enemies with low health away (shock is the strongest, fire is the weakest), while journeyman with frost duration spells will cause paralysis based on fatigue amount. Less fatigue increases paralysis chance.
#### Damage Stat Effects - Diseases
All standard Damage stat spells have a chance to inflict a random disease on targets including yourself, making these spells a bit more worth the additional cost while also making diseases spreadable to enemies. Disease resistance will naturally affect disease chance on enemies and yourself, chance is 50% higher than natural spread.
#### Disintegrate Duration Fix
Custom made disintegrate armor and weapon spells with a duration will now work. The additional damage over time is unaffected by spell magnitude but takes about 30 seconds to fully destroy a single items health.
#### Poison Spells
These journeyman and expert spells modify all subsequent spells cast at the target during the effect to be classed as a poison. This means weakness to poison/resist poison now effect the spells cast so you can bypass resistance to magic effects on enemies. 
Undead, Redguards and Argonians have strong poison resistance naturally so it is best to avoid using on those npcs as your spells may lose effectiveness instead.
***
### <p align="center"> CONJURATION
There are now consequences to summoning the dead due to the Mages Guild ban on necromancy, and to summoning daedra due to the ongoing Oblivion crisis. These two changes really make Conjuration feel like a dark and taboo school of magic. <br/>

Necromancy was banned by the Mages Guild, and if you summon undead near a Mages Guild member you will be expelled from the guild. In addition, while not illegal in the lore, summoning undead will result in a 100-gold bounty if done near a guard. (Note: This bounty is only added if a guard is nearby. Casting near citizens/other NPCs will not result in a bounty). <br/>

As for daedric summons, while Conjuration has been an accepted school of magic in the past, in light of recent events the public perception has gone decidedly downhill. It's not illegal or anything, but absolutely frowned upon and most folk no longer trust it nor the mages who practice it. Summoning daedra while detected by a friendly npc will now add 1 point of infamy to the player. <br/>

All summons now have a graphical effect to make it clear these are summons and not standard enemies. There is also a reanimate spell you can buy from a shady source, and reanimation effects from standard sources (not custom spells) additionally work on dead creatures, not just npcs.
#### New summons
Conjuration is the art of summoning Daedra so it makes sense various shivering isle creatures can be summoned as they are daedric creations of Sheogorath. All Shivering Isles summons have a chance to summon the mania or dementia version of them. Note all new summon spells will not replace existing standard summons when cast. They can only be cast when other summons expire. They can be cast to replace themselves though.
#### Longer Lasting spells
Conjuration spells never last very long (Many at 15 seconds) so I have tweaked magic effects directly to at last be of use.
#### Bound Weapons
Based on your Conjuration level, you unlock the following perks for bound weapons: <br/>

Conjuration 25 – Soul Stealer
Your bound weapons automatically cast Soul Trap on hit.

Conjuration 50 – Mystic Binding: Rank 1
Your bound weapons deal increased damage (+3).

Conjuration 60 - Hollow Binding
Bound weapons lower targets magic resist by 15% on hit for 10 seconds.

Conjuration 75 – Oblivion Binding
Bound weapons will banish level 15 or lower Daedra, and turn Undead level 15 or lower.
Daedra above level 15 will instead take 10 points of Shock damage.

Conjuration 90 – Mystic Binding: Rank 2
Your bound weapons deal additional increased damage (+3). (Stacks with Rank 1 for +6 total).

Conjuration 100 - Elemental Conflux
While near an elemental atronach you've summoned, bound weapons deal 10 points of elemental damage. (Element is based on atronach).
#### Necromancy
Each filled Black Soul Gem in your inventory will increase the combat related attributes and skills of your undead summons by two points each. This buff maxes-out when you have 30 Filled Black Soul Gems. This gives Necromancer players a reason to stockpile Black Soul Gems beyond enchanting and roleplaying reasons.

In addition to scaling power, you now unlock unique perks as you collect more souls:<br/>

  5 Souls – Gravehide: Undead Summons gain +15 Resistance to Normal Weapons<br/>
  10 Souls – Soulshroud: Undead Summons gain +15 Magic Resistance<br/>
  15 Souls – Dark Conduit: While in combat with an undead summon, you regenerate an additional 1 magicka per second.<br/>
  20 Souls – Chill of the Crypt: Undead Summons have a 25% chance to apply a movement speed debuff to enemies when hit. Summons also gain an additional +15 to both Weapon and Magic Resistances.<br/>
  25 Souls - Master of Death: You gain the "Risen Flesh﻿" Power. Allowing you to resurrect dead bodies.<br/>
***
### <p align="center"> MYSTICISM
#### Telekinesis
Telekinesis spells (not custom spells) have been overhauled into really useful utility spells. They can loot chests, open doors, loot dead bodies and pick up items. You can only loot dead bodies while crouched, as the remaster has a new feature allowing you to move bodies with telekinesis. If you cast telekinesis on a living npc or creature you will quickly position yourself behind their back which is great for pickpocketing or sneak attacks.

#### Siphon Pain / Absorb Damage
New Siphon Pain spell similar to spell absorption effects has a chance to absorb physical damage and refill your magicka.

#### Soul Trap
Soul trap is a bit tedious to use. So now on every hit of the spell, a little bit of your enemies soul 5% will be saved while you have empty soul gems. Once enough soul energy has been saved this will fill a soul gem for you. This will only fill the soul gem entirely and not partly fill one with a lesser soul. As your mysticism mastery level increases you will save more soul energy allowing you to more quickly fill soul gems. Same rules apply only creatures can fill normal soul gems, while black soul gem can also use npcs.

#### Dispel
Standard target Dispel effects and enchantments (not custom spells) now cause high damage to summons. Useful if the dispel is not powerful enough to dispel the summon spell itself from an enemy caster.  

#### Extrication / Emergency Teleport
Teleportation spells were a staple in Morrowind but became less critical with fast travel. The new **Extrication** spell lets you teleport to your last known safe outdoor location: Quickly return to dungeon entrances or escape from combat (works both indoors and outdoors). The spell has a casting delay during which you’re vulnerable as you are paralyzed. It cannot be used in certain locations (e.g., jail, arena, or designated quest areas).

#### Mark/Recall (Teleport)
﻿The classic Morrowind Mark and Recall spells have been added to vendors for teleporting to custom locations. These spells include a brief casting delay similar to Extrication: Once you mark a location, it leaves a wisp at the location and remains active until you travel to the Shivering Isles (or vice versa) or are taken to jail. In such cases, you’ll need to cast ﻿a new mark. This functionality is especially useful when fast travel is disabled. Exercise caution: Remember that recalling into an area with no exit may break ﻿your game.


#### Create/Enchant spell
Spell Weave (Mysticism): Allow to create a spell outside the University and without a spellmaking altar.
Spell Forge (Mysticism): Allow enchanting of items without an enchanting altar.

#### Spellfire
Mystics now have the ability to defeat other mages easily with the Spellfire spells. These damage enemies whenever they cast a spell. Entire guilds of mages can wipe themselves out with ease. There is a single target spell and a very powerful area effect spell.

#### Magic effect Weakness Spell Schools
Weakness to magic - is now under the mysticism skill which fits lore that mysticism is around modifying magic.

#### Absorb Mysticism School 
Mysticism typically lacks offensive spells, which makes leveling it challenging. This changes that back to just like it was in morrowind. Absorb spells range limit is now twice as long, especially as remaster has no visual effect to show this limitation. Standard absorb magicka spells include a fortify magicka on the opponent, as unlike other absorb spells this ends or never starts if there is no magicka to absorb which made them useless. They are already very difficult to use as early game they cost more than what you absorb.
***
### <p align="center"> ALTERATION

#### Force Spells
This provides more offensive capabilities to alteration mages while still fitting the theme of supporting magic as these cannot kill people unless gravity is involved. The spells alter the air to create a force of wind to blow enemies away. There is a small chance for enemies to be unaffected based on your willpower and luck skills.

#### Blink
Based on similar techniques to morrowinds levitation, this simpler spell instead makes you travel a distance forwards in a small amount of time. Just look in direction you want to go and cast spell.

#### Spell Improvements

- Burden spells are pretty much useless for the player. Now when burden spells (not custom spells) are cast on an enemy it will root them to the spot for a few seconds while they deal with the sudden weight increase. It ranges from 1-5 seconds based on alteration skill. This provides slight offensive capability until you can use the force spells.
- Feather effects now protect you against fall damage. Note that this protection is negated if burden effects are active.
- Waterbreathing effects provide a small boost to swimming speed during its effect.
- Elemental shield effects including custom spells now cause small amounts of AOE damage per second in melee combat. This affects both yourself and enemies. This damage scales with your resistance to element and alteration skill, although there is a hard cap of 10 per second to avoid it being overpowered.

#### Levitation
While levitating, you lose 10 magicka per second. When you run out of magicka, levitation is dispelled. You can recast Levitation to dispel it early.

#### Magic effect Weakness Spell Schools
Weakness to normal weapons is now under the alteration skill which fits lore you can weaken armor. Also provides more offensive capability to the school.
***
### <p align="center"> ILLUSION

#### Invisibility 
Invisibility effects now take a toll to maintain and will prevent magicka regen during its effect. This is to prevent abusing very low cost invisibility spells. Buy the higher cost and run away.

#### Paralyze
Paralyze spells are very powerful, so now they have an additional % chance to fail on all enemies based on your illusion skill and luck. At level 1 without mods its 25% resistance, then about 0% at/over 100 skill.

#### Chameleon God Mode Fix
Chameleon is pretty broken at 100% effect as no one will interact with you in combat so the effect is now capped at 99% to disable god mode. If you crouch enemies will completely lose you (similar to 100%) and will eventually end combat. This only lasts for 10-15 seconds based on sneak skill. If you uncrouch effect will be lost. After effect has expired there is a number of seconds must pass (based on sneak) and you must be uncrouched. Then you can crouch and use the same tactic again. You will see messages when its possible to crouch or the effect has ended.

#### Night Eye
Higher level night eye spells/potions (spells with long durations) dynamically detect daylight and disable the night eye effect until your back in an area which needs it. This reduces the annoyance of the effect. Additionally you are given a"Night eye control" power to manually turn the night eye effect on and off while spell is active. Note when the location lighting changes again this will override your manual toggle. This does not affect/apply to lower skill night eye ,custom spells and enchantments where night eye is always maintained. Night eye now makes it easier to find items compared to previously and will illuminate corpses.

#### Magic effect Weakness Spell Schools
Resist normal weapons - This magic effect is now under the illusion skill like in morrowinds (sanctuary) rather than restoration, and its commonly present on ghosts which are not anywhere near the restoration spell school.
Weakness to poison - is now under the illusion skill which fits lore that by confusing the mind or hiding the poisons presence its easier to distribute the poison for maximum effect.
***
### <p align="center"> RESTORATION

#### Spells Restore Over Time
Spells which Restore Health or Fatigue now do so over time instead of instantly on cast.

#### Turn Undead Restoration School 
Ever noticed that Turn Undead spells are sold by priests yet classified under Conjuration? This is changed and now provides more offensive capability to this school and also fits its theme better.

#### Magic effect Weakness Spell Schools
Weakness to disease is under the restoration skill as modifying the health of someone you could exploit to make them prone to disease. This provides more offensive capability which you can pair with the new disease effect from damage health.
***
