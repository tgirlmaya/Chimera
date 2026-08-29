---
publish: true
aliases:
  - Staff of Power
created: 2026-08-28T20:41:12.724Z
modified: 2026-08-29T18:07:49.671Z
tags:
  - ttrpg-cli/compendium/src/5e/xdmg
  - ttrpg-cli/item/attunement/required
  - ttrpg-cli/item/rarity/very-rare
  - ttrpg-cli/item/weapon/melee
  - ttrpg-cli/item/weapon/simple
cssclasses:
  - json5e-item
---

# Staff of Power

_Staff, weapon, very rare (requires attunement by a sorcerer, warlock, or wizard)_\
![](Compendium/Mechanics/CLI/items/img/staff-of-power.webp#right)

- **Damage**:
  - One-handed: 1d6 bludgeoning
  - Two-handed: 1d8 bludgeoning
- **Properties**: [Versatile](Compendium/Mechanics/CLI/Rules/item-properties.md#Versatile)
- **Weight**: 4.0 lbs.

This staff has 20 charges and can be wielded as a magic Quarterstaff that grants a +2 bonus to attack rolls and damage rolls made with it. While holding it, you gain a +2 bonus to [Armor Class](Compendium/Mechanics/CLI/Rules/variant-rules/armor-class-xphb.md), saving throws, and spell attack rolls.

## Spells

While holding the staff , you can cast one of the spells on the following table from it, using your spell save DC. The table indicates how many charges you must expend to cast the spell.

| Spell | Charge Cost |
|-------|-------------|
| [Cone of Cold](Compendium/Mechanics/CLI/spells/cone-of-cold-xphb.md) | 5 |
| [Fireball](Compendium/Mechanics/CLI/spells/fireball-xphb.md) (level 5 version) | 5 |
| [Globe of Invulnerability](Compendium/Mechanics/CLI/spells/globe-of-invulnerability-xphb.md) | 6 |
| [Hold Monster](Compendium/Mechanics/CLI/spells/hold-monster-xphb.md) | 5 |
| [Levitate](Compendium/Mechanics/CLI/spells/levitate-xphb.md) | 2 |
| [Lightning Bolt](Compendium/Mechanics/CLI/spells/lightning-bolt-xphb.md) (level 5 version) | 5 |
| [Magic Missile](Compendium/Mechanics/CLI/spells/magic-missile-xphb.md) | 1 |
| [Ray of Enfeeblement](Compendium/Mechanics/CLI/spells/ray-of-enfeeblement-xphb.md) | 1 |
| [Wall of Force](Compendium/Mechanics/CLI/spells/wall-of-force-xphb.md) | 5 |
^spell-charge-cost

## Regaining Charges

The staff regains `2d8 + 4` expended charges daily at dawn. If you expend the last charge, roll `1d20`. On a 1, the staff retains its +2 bonus to attack rolls and damage rolls but loses all other properties. On a 20, the staff regains `1d8 + 2` charges.

## Retributive Strike

You can take a [Magic](Compendium/Mechanics/CLI/Rules/actions.md#Magic) action to break the staff over your knee or against a solid surface. The staff is destroyed and releases its magic in an explosion that fills a 30-foot [Emanation](Compendium/Mechanics/CLI/Rules/variant-rules/emanation-area-of-effect-xphb.md) originating from itself. You have a 50 percent chance to instantly travel to a random plane of existence, avoiding the explosion. If you fail to avoid the effect, you take Force damage equal to 16 times the number of charges in the staff. Each other creature in the area makes a DC 17 Dexterity saving throw. On a failed save, a creature takes Force damage equal to 4 times the number of charges in the staff. On a successful save, a creature takes half as much damage.

_Source: Dungeon Master's Guide (2024) p. 308. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)_
