![banner image](https://raw.githubusercontent.com/sasquatch678/A-Painted-World---Remastered/refs/heads/main/Images/arena.png)

***

# <p align="center">COMBAT</p>

<p align="center">
[ <a href="https://github.com/sasquatch678/A-Painted-World---Remastered/blob/main/Gameplay/Combat.md#weapons">Weapons</a> |
  <a href="https://github.com/sasquatch678/A-Painted-World---Remastered/blob/main/Gameplay/Combat.md#dodging">Dodging</a> |
  <a href="https://github.com/sasquatch678/A-Painted-World---Remastered/blob/main/Gameplay/Combat.md#block">Block</a> |
  <a href="https://github.com/sasquatch678/A-Painted-World---Remastered/blob/main/Gameplay/Combat.md#marksman">Marksman</a> |
  <a href="https://github.com/sasquatch678/A-Painted-World---Remastered/blob/main/Gameplay/Combat.md#slowmo">SloMo</a> ]
</p>

***

Weapon balance has been completely overhauled. Weapon weight has been reduced by roughly 50% across the board. Weapon health and value have been adjusted so items degrade more slowly, while mid–endgame gold generation is slightly reduced to increase economic pressure.

Using a refined length-based formula, every weapon now closely matches its mesh length in-game, making reach more consistent, fair, and reactive. Creature reach values have been adjusted to follow the same system.

Enemy AI has also been reworked to be more aggressive. Idle time between attacks has been reduced, and enemies now chain attacks more frequently and consistently. They also dodge and block more often, creating a faster, more continuous combat flow where every exchange matters.

The difficulty system in Oblivion Remastered was heavily inconsistent. Novice was trivial, Apprentice only slightly better, Adept reasonable, and higher settings often unplayable. In A Painted World, scaling has been normalized so each difficulty serves a meaningful role.

>[!TIP]
>You can configure these multipliers by pressing F12 and opening the in-game MCM.<br/>

### VANILLA
<p align="center">
![banner image](https://raw.githubusercontent.com/sasquatch678/A-Painted-World---Remastered/refs/heads/main/Images/vanillascaling.png)
</p>

### APWR
<p align="center">
![banner image](https://raw.githubusercontent.com/sasquatch678/A-Painted-World---Remastered/refs/heads/main/Images/apwrscaling.png)
</p>

Overall, combat is designed to feel quick, lethal, and fair for both player and NPCs.

Recommended settings:
- Enemy damage: Journeyman  
- Player damage: Adept or Journeyman  

Adjust based on build, progression, or preference.

>[!TIP]
>Most features below can be configured in the in-game MCM (F12).<br/>

***

## WEAPONS

No more “paddle” weapons. Blunt and blade archetypes are now clearly differentiated:

- **Blunt:** higher base damage, lower reach, slower speed, higher stagger potential  
- **Blade:** higher reach, faster speed, lower base damage, higher critical potential  

All weapons can now stagger and critically strike:
- Blunt weapons: higher stagger chance  
- Blade weapons: higher crit chance  
- Power attacks: +100% stagger chance for all weapons  
- Stagger scales with attacker Strength vs defender Endurance  
- Crit chance scales with attacker Luck  

### Mechanics
- Power attacks use a single button (no hold input)  
  - KB&M: MB5  
  - Controller: L3/LS + attack  
- Counterattacks (Perfect Dodge/Block within 5s window): +10–30% damage  
- Counterattacks may ragdoll enemies based on Strength roll  
  - Every 10 Strength = 9% resistance  

***

## LOCK-ON

- Third-person lock-on with target cycling and body-part targeting  
- Hold Alt (KB&M) / Hold A (Controller) to activate  
- Default target point: Spine  
- Optional “Enemies Only” filter (disabled by default)  
- Cycling: Z/X (KB&M), Right Stick (Controller)  
- Body-part cycling: quick-tap lock-on while already locked  

***

## DODGING

Requirements:
- Minimum 25 Acrobatics  
- Cannot dodge while crouched, out of fatigue, or over-encumbered (configurable)  

Core mechanics:
- Tap Control (KB&M) / Tap B (Controller) to dodge  
- Hold for sneak (context dependent)  
- 0.4s damage resistance during dodge window  
  - Scales with Acrobatics (2× skill, up to 100%)  
  - Physical only (magic/special materials bypass)  
- Fatigue cost: base 20 + skill modifier (lower skill = higher cost)  
- Dodge allows attack cancellation with weapon-specific timing  

### Perfect Dodge
- Requires Acrobatics 100  
- Grants iframe window (perfect timing only)  
- +30% movement speed for 5s counter window  
- 0.2s timing window determines response attack bonus (10–30%)  
- Reticle changes color during window  

***

## BLOCK

- Blocking can cancel attacks using weapon-specific timing  
- Cancelled attacks still consume equivalent fatigue  

### Perfect Block
- 0.3s precision window during enemy attack  
- 50–90% damage reduction (scales with Block skill)  
- Staggers enemy and triggers 2s slow-motion  
- Opens 5s response window (+10–30% damage based on timing)  
- Reticle changes color during window  

### Feint / Attack Cancel
- Early cancel: bait enemy reactions  
- Late cancel: combo reset after hit  
- Fully timing-based per weapon type  

***

## MARKSMAN

- Instant Draw unlocked at 50+ Marksman (or via Perfect Dodge/Block buff)  
- Release animation cancel at 50+ Marksman (or buffed state)  
- Rapid Shot enabled during 5s Perfect Dodge/Block window  
- At Marksman 75 + Acrobatics 75: unlock slow-motion bow jump with featherfall  

### Headshots
- Damage scales with Marksman + Sneak  
  - 1.1× to 2× Marksman scaling  
- Sneak adds up to +50% bonus (at 100 Sneak, undetected)  
- Reticle indicates headshot window  

***

## SLOWMO

### Hitstop
- Weapon-specific intensity and duration  
- Modified by attack type (light, power, sneak, block)  
- Internal cooldown prevents stacking with global slow-motion systems  

### Killcam
- 50% chance on kills  
- 100% chance on:
  - Headshots  
  - Perfect Dodge/Block kills  
  (excluded if target HP < 50% player max HP to avoid trash mob triggers)  
- 2s global duration  
- 40% playback speed  

### Quickwheel
- Time slows to 20% when opened  

***
