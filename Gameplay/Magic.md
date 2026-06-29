![banner image](https://raw.githubusercontent.com/sasquatch678/A-Painted-World---Remastered/refs/heads/main/Images/magealchemy.png)

# <p align="center">MAGIC</p>

<p align="center">
[ Destruction | Conjuration | Mysticism | Alteration | Illusion | Restoration ]
</p>

---

## Magic System Overview

Magic has been lightly overhauled to improve leveling balance, expand underused mechanics, and reinforce each school’s identity.

Key system changes:

- Staffs now scale Magicka and regeneration while equipped, scaling with Willpower
- Robes no longer occupy lower body slots (enabling additional enchantment slots)  

>[!TIP]
>Robes can cause clipping when combined with certain armor sets. This can be disabled via optional MO2 configuration.

---

## MAGIC SKILL LEVELING (REWORKED)

### Spell Cost XP Fix

Oblivion Remastered introduced XP scaling based on **base spell cost**, which unintentionally caused:

- Faster leveling at high skill levels  
- Imbalanced progression between early and late game spells  

This has been corrected so XP now scales with:

- **Actual Magicka cost (post-modifiers)**

This restores consistent progression across all skill levels.

---

### Flat XP Removal

The original “flat XP per cast” system has also been removed because:

- It disproportionately benefited expensive schools (e.g. Conjuration)  
- It encouraged inefficient spam casting in low-cost schools  

Magic progression is now fully unified under cost-based XP only.

---

# MAGIC SCHOOL CHANGES

---

## DESTRUCTION

### Core Changes

Elemental spells now include secondary effects:

- **Fire:** Damage over time  
- **Frost:** Fatigue damage
- **Shock:** Magicka damage  

⚠️ Effects can also apply to the caster if hit by reflected spells.

At higher ranks:
- Duration spells gain knockback effects (shock strongest, fire weakest)
- Frost paralysis scales with target fatigue

---

### Status Effects

- Damage attribute spells may apply disease (including self-risk)  
- Disease spread chance is increased over vanilla behavior  
- Resistance reduces infection chance normally  

---

### Disintegration Fix

- Duration-based disintegrate effects now properly tick over time  
- Fully destroys target equipment in ~30 seconds (based on effect strength)

---

### Poison Conversion (Advanced Effects)

High-level Destruction spells can:

- Convert subsequent spell effects into “poison-tagged” damage  
- Allow bypassing Magic Resistance via Poison Resistance interactions  

⚠️ Strongly resisted by:
- Undead  
- Redguards  
- Argonians  

---

## CONJURATION

### Legal & Social Consequences

Conjuration is now a socially and politically controversial school:

- **Undead summoning near Mages Guild members → expulsion**
- **Undead summoning near guards → 100 gold bounty (if detected)**
- **Daedra summoning (detected by NPCs) → +Infamy**

---

### Summoning Improvements

- Summons now have clear visual effects  
- Shivering Isles creatures added as summon variants  
- Mania/Dementia variants can randomly appear  
- Summons persist properly before replacement is allowed  

---

### Bound Weapon Progression

Bound weapons now scale with Conjuration skill:

- **25:** Soul Trap on hit  
- **50:** +Damage (Rank 1)  
- **60:** Magic Resistance reduction on hit  
- **75:** Banish/Turn undead scaling effect  
- **90:** +Damage (Rank 2, stacks)  
- **100:** Elemental bonus near atronachs  

---

### Necromancy System

Black Soul Gems directly empower undead summons:

- Each filled gem grants scaling stat bonuses  
- Caps at 30 filled Black Soul Gems  

Unlock milestones:

- 5: Weapon resistance  
- 10: Magic resistance  
- 15: Magicka regeneration in combat  
- 20: Slow effect on hit + defensive bonuses  
- 25: Unlock **Risen Flesh (resurrection power)**  

---

## MYSTICISM

### Utility Overhaul

Mysticism is now a true utility/control school:

- Telekinesis can loot, open, and manipulate objects  
- Can reposition NPCs for stealth or pickpocket setups  
- Crouch-based corpse interaction added  

---

### Soul Mechanics

- Partial soul collection now fills gems gradually  
- Efficiency increases with skill level  
- Black Soul Gems can absorb humanoid souls  

---

### New Utility Spells

- **Extrication:** Teleport to last safe outdoor location (with casting delay)  
- **Mark/Recall:** Classic Morrowind-style teleport system  
- **Spell Weave / Spell Forge:** Enchanting & spellcraft outside altars  

---

### Combat Tools

- Spellfire punishes enemy spellcasting  
- Absorb Magicka improved with scaling mechanics  
- Dispel now damages summons  

---

## ALTERATION

### Mobility & Control

- Force spells push enemies (non-lethal unless environmental kill)  
- Blink replaces short-range movement  
- Levitation drains Magicka per second  

---

### Defensive Reworks

- Burden roots enemies briefly (1–5s scaling)  
- Feather prevents fall damage (cancelled by Burden)  
- Waterbreathing improves swim speed  
- Elemental Shields now emit AoE damage in melee  

---

### School Identity Shifts

- Weakness to Normal Weapons → Alteration  
- Weakening armor and physical defense is now core Alteration identity  

---

## ILLUSION

### Stealth & Mind Control

- Invisibility disables Magicka regeneration  
- Paralyze now has success chance scaling with skill + Luck  
- Chameleon capped at 99% (no full god mode)  

---

### Advanced Stealth System

- 100% Chameleon replaced with “stealth fade window”  
- Crouch-based detection reset mechanics added  
- Encourages timing-based stealth instead of permanent invisibility  

---

### Night Eye Improvements

- Automatically disables in daylight  
- Manual toggle power added  
- Corpses and items highlighted more clearly  

---

### School Identity Shifts

- Resist Normal Weapons moved to Illusion  
- Weakness to Poison moved to Illusion  
- Sanctuary-style effects now fully part of Illusion identity  

---

## RESTORATION

### Healing Over Time

- Healing and fatigue restoration now applies over time instead of instantly  

---

### School Identity Shifts

- Turn Undead moved from Conjuration → Restoration  
- Weakness to Disease now part of Restoration  
- Restoration gains more offensive synergy tools  

---
