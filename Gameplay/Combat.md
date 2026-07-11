![banner image](https://raw.githubusercontent.com/sasquatch678/A-Painted-World---Remastered/refs/heads/main/Images/arena.png)
***
# <p align="center"> COMBAT
<p align="center">
[ <a href="https://github.com/sasquatch678/A-Painted-World---Remastered/blob/main/Gameplay/Combat.md#weapons">Weapons</a> |
  <a href="https://github.com/sasquatch678/A-Painted-World---Remastered/blob/main/Gameplay/Combat.md#dodging">Dodging</a> |
  <a href="https://github.com/sasquatch678/A-Painted-World---Remastered/blob/main/Gameplay/Combat.md#block">Block</a> |
  <a href="https://github.com/sasquatch678/A-Painted-World---Remastered/blob/main/Gameplay/Combat.md#marksman">Marksman</a> |
  <a href="https://github.com/sasquatch678/A-Painted-World---Remastered/blob/main/Gameplay/Combat.md#slowmo">SloMo</a> ]
</p>
The difficulty settings in Oblivion Remastered are a total mess. Novice is a joke, Apprentice isn't much better, Adept is fine and everything else is borderline unplayable. In A Painted World these difficulty settings have been brought closer together so that each selection actually serves a purpose. A detailed breakdown is below.

>[!TIP]
>You can configure these multipliers by pressing F10 and navigating the MCM ingame.<br/>
#### <p align="center"> ![banner image](https://raw.githubusercontent.com/sasquatch678/A-Painted-World---Remastered/refs/heads/main/Images/new%20difficulty.png)

Weapon balance has also been completely overhauled. Firstly, weapon weight has been cut by about half across the board, and weapon health and values have been tweaked to have more health (degrade slower) and a bit less value, so that mid - endgame is a bit harder to make gold. Next, using a very accurate formula, every weapon will now very closely match with the length of their mesh in the game, which means combat should overall feel much more fair and responsive. </br>

Enemy AI has also been overhauled to be more aggressive, with lower idle times between attacks. Enemies before would attack and then stand for sometimes seconds at a time, as if they weren't actually fighting for their lives. Now enemies fight as if their life depends on it. They chain attacks, fast and consistently. Enemies are also more likely to dodge and block your attacks, making for a more fast paced and engaging system where action never stops, and every hit matters.

Because of all of this, combat should feel quick, lethal, and fair for both the player and npcs. I recommend playing on Journeyman difficulty for enemy damage, and Adept/Journeyman for player damage for a moderate challenge that won't get you killed too often (as long as you are playing well), though you may wish to change these based on preference, build, or character progression. <br/>

***
## WEAPONS
***
No more different modeled paddles! Blunt weapons tend to have high base damage, but low reach and low speed. Blade weapons have higher reach and speed, but lower base damage.

All weapons can now cause stagger and critically strike. Blunt weapons have a much higher chance to cause stagger, while Blade weapons have a higher chance to critically strike. The exact amounts depend on the specific weapon type. Stagger chance is also doubled with power attacks for all weapons. Stagger is based on the attacker's Strength and the victim's Endurance, and critical strikes are based on the attacker's Luck.

- Can perform power attacks with one button (default mouse button 4) instead of holding left click.
- 10% to 30% damage buff on counter attacks from Perfect Dodge/Block within 5s window.
- Counter attacks ragdoll the enemy based on an enemy strength roll, each 10 strength give 9% resistance
***
## DODGING
>[!TIP]
>Most of the below features can be configured in mods\Ultra Combat V2 - Fixed Edition\UE4SS\UltraCombat\scripts\config.lua. You can find valid key inputs [here](https://unrealcommunity.wiki/list-of-key/gamepad-input-names-j9c5mqou) to change keybinds.<br/>
***
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
***
## BLOCK
***
- Blocking can attack cancel using the same weapon and attack specific timings as Dodge.
- Block attack cancelling will cost the equivalent fatigue as the cancelled attack would have.

#### Perfect Block
- Perfect Block provides a window of opportunity (0.3s) during an opponents attack.
- Perfect Block further reduces damage based on block skill (50% to 90%), staggers the enemy, begins a slomo for 2s, and opens a 5s window a “Response Attack” which provides a 10-30% dmg boost based on timing.
- Reticle will change colors to indicate Perfect Block counter windows.

#### Attack Cancel / Feint
- Feint window - Cancel attacks early (before hit) to bait reactions with weapon and attack specific timings for an immersive combat feel
- Combo breaking - Cancel attacks late (after hit) to reset
***
## MARKSMAN
***
- Instant Draw unlocked at 50+ Marksman or with Perfect Block/Dodge Buff.
- Release Animation Cancel at 50+ Marksman or with Perfect Block/Dodge Buff.
- Rapid Shot response for Perfect Block/Dodge, 5s window.
- At Marksman 75, Acrobatics 75, unlocks a slowmo bow jump with featherfall.

#### Headshot 
- Headshot damage based on marksman & sneak skill- 1.1x to 2x for Marksman.
- Sneak damage is additive on top of headshot damage, up to +50% sneak damage (at 100 Sneak) if undetected.
- Reticle will change colors to indicate Headshot.
***
## SLOWMO
***
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
***
