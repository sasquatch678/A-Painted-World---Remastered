# Combat

In Oblivion, players can become so powerful at high levels that the game turns boring. When most enemies pose little to no threat, encounters lose their appeal, and without any challenge, the fun fades away. Raising the difficulty helps, but it is not an ideal solution. Not only does doing so undermine the player’s sense of progression (by making them arbitrarily weaker), it also makes proper high level enemies overly challenging. This causes players to constantly adjust the difficulty just to enjoy the game again. <br/>

A Painted World addresses these issues by making the player’s power conditional on skillful play. Now when struck by a weapon or spell you fail to dodge or block, you’ll suffer damage-over-time effects; Bleed for physical hits and Spell Burn for magical ones. These effects scale with your max health and stack with each hit, causing damage to escalate rapidly if you’re careless. These new mechanics result in a gameplay loop that incentives you to take every fight seriously because if you don't, you'll die. <br/>

Enemy AI has also been overhauled to be more aggressive, with lower idle times between attacks. Enemies before would attack and then stand for sometimes seconds at a time, as if they weren't actually fighting for their lives. Now enemies fight as if their life depends on it. They chain attacks, fast and consistently. Enemies are also more likely to dodge and block your attacks, making for a more fast paced and engaging system where action never stops, and every hit matters.

Because of this, combat should feel quick and lethal for both the player and npcs. I recommend playing on Journeyman difficulty for enemy damage, and Adept for player damage, though you may wish to change these based on preference, build, or character progression. There are also several new mechanics you can take advantage of listed below. Most of these features can be configured in mods\Ultra Combat UE4SS V2 - Physical Combat Overhaul\UE4SS\UltraCombat\scripts\config.lua. You can find valid key inputs [here](https://unrealcommunity.wiki/list-of-key/gamepad-input-names-j9c5mqou).<br/>

## Dodging
- Requires a minimum 25 in Acrobatics
- Dodge by tapping mouse button 5.
- Dodging is blocked while the player is crouched, out of fatigue, and/or over encumbered, configurable.
- During dodges, for 0.4s the player will have resistance to normal weapons based on acrobatics skill (2x skill, max 100%). Magic and special weapon materials can penetrate the physical barrier it provides.
- Fatigue drain for dodging is based on acrobatics skill. Base 20 + Skill Modifier (Lower skill = More Fatigue Cost)
- Dodges allow attack cancelling, which has timings based on attack type and weapon.

#### Perfect Dodge
- Perfect Dodge at Acrobatics 100 provides an "iframe" (invulnerability).
- Perfect Dodge gives a 30% speed boost during 5s counter attack window.
- Perfect Dodging has a 0.2s window-  the closer you are to the perfect frame on a dodge during enemy attack, the more damage your “Response Attack” will get (10%-30%).
- Reticle will change colors to indicate Perfect Dodge counter windows.

## Block
- Blocking can attack cancel using the same weapon and attack specific timings as Dodge.
- Block attack cancelling will cost the equivalent fatigue as the cancelled attack would have.

#### Perfect Block
- Perfect Block provides a window of opportunity (0.3s) during an opponents attack.
- Perfect Block further reduces damage based on block skill (50% to 90%), staggers the enemy, begins a slomo for 2s, and opens a 5s window a “Response Attack” which provides a 10-30% dmg boost based on timing.
- Reticle will change colors to indicate Perfect Block counter windows.


## Melee Weapons & H2H
- Can perform power attacks with one button (default mouse button 4) instead of holding left click.
- 10% to 30% damage buff on response attacks from Perfect Dodge/Block within 5s window.
- Ragdoll's enemy based on an enemy strength roll, each 10 strength give 9% resistance

#### Attack Cancel / Feint
- Feint window - Cancel attacks early (before hit) to bait reactions with weapon and attack specific timings for an immersive combat feel
- Combo breaking - Cancel attacks late (after hit) to reset

## Marksman
- Instant Draw unlocked at 50+ Marksman or with Perfect Block/Dodge Buff.
- Release Animation Cancel at 50+ Marksman or with Perfect Block/Dodge Buff.
- Rapid Shot response for Perfect Block/Dodge, 5s window.
- At Marksman 75, Acrobatics 75, unlocks a slowmo bow jump with featherfall.

#### Headshot 
- Headshot damage based on marksman & sneak skill- 1.1x to 2x for Marksman.
- Sneak damage is additive on top of headshot damage, up to +50% sneak damage (at 100 Sneak) if undetected.
- Staggers the enemy if they survive.
- Reticle will change colors to indicate Headshot.

## SlowMo

#### Hitstop
- Weapon-specific duration and intensity.
- Attack type modifiers (light, power, sneak, blocked).
- Cooldown system to prevent overlap with main slowmo effects.

#### Killcam
- Occurs on 50% of all kills. Then, will occur on 100% of all headshots and perfect dodge/block(s) unless the enemy's max health is below 50% of the players max health (this is to prevent slowmo's on trash mobs)
- Global 2s duration.
- Slows to 40% speed.

#### Quickwheel
- Will slow to 10% upon opening the quick wheel.
