---
publish: true
aliases:
  - Staff of the Magi
created: 2026-08-28T20:41:12.732Z
modified: 2026-08-29T18:07:49.579Z
tags:
  - ttrpg-cli/compendium/src/5e/xdmg
  - ttrpg-cli/item/attunement/required
  - ttrpg-cli/item/rarity/legendary
  - ttrpg-cli/item/weapon/melee
  - ttrpg-cli/item/weapon/simple
cssclasses:
  - json5e-item
---

# Staff of the Magi

_Staff, weapon, legendary (requires attunement by a sorcerer, warlock, or wizard)_\
![](Compendium/Mechanics/CLI/items/img/staff-of-the-magi.webp#right)

- **Damage**:
  - One-handed: 1d6 bludgeoning
  - Two-handed: 1d8 bludgeoning
- **Properties**: [Versatile](Compendium/Mechanics/CLI/Rules/item-properties.md#Versatile)
- **Weight**: 4.0 lbs.

This staff has 50 charges and can be wielded as a magic Quarterstaff that grants a +2 bonus to attack rolls and damage rolls made with it. While you hold it, you gain a +2 bonus to spell attack rolls.

## Spell Absorption

While holding the staff , you have [Advantage](Compendium/Mechanics/CLI/Rules/variant-rules/advantage-xphb.md) on saving throws against spells. In addition, you can take a [Reaction](Compendium/Mechanics/CLI/Rules/variant-rules/reaction-xphb.md) when another creature casts a spell that targets only you. If you do, the staff absorbs the magic of the spell, canceling its effect and gaining a number of charges equal to the absorbed spell's level. However, if doing so brings the staff's total number of charges above 50, the staff explodes as if you activated its Retributive Strike (see below).

## Spells

While holding the staff, you can cast one of the spells on the following table from it, using your spell save DC. The table indicates how many charges you must expend to cast the spell.

| Spell | Charge Cost |
|-------|-------------|
| [Arcane Lock](Compendium/Mechanics/CLI/spells/arcane-lock-xphb.md) | 0 |
| [Conjure Elemental](Compendium/Mechanics/CLI/spells/conjure-elemental-xphb.md) | 7 |
| [Detect Magic](Compendium/Mechanics/CLI/spells/detect-magic-xphb.md) | 0 |
| [Dispel Magic](Compendium/Mechanics/CLI/spells/dispel-magic-xphb.md) | 3 |
| [Enlarge/Reduce](Compendium/Mechanics/CLI/spells/enlarge-reduce-xphb.md) | 0 |
| [Fireball](Compendium/Mechanics/CLI/spells/fireball-xphb.md) (level 7 version) | 7 |
| [Flaming Sphere](Compendium/Mechanics/CLI/spells/flaming-sphere-xphb.md) | 2 |
| [Ice Storm](Compendium/Mechanics/CLI/spells/ice-storm-xphb.md) | 4 |
| [Invisibility](Compendium/Mechanics/CLI/spells/invisibility-xphb.md) | 2 |
| [Knock](Compendium/Mechanics/CLI/spells/knock-xphb.md) | 2 |
| [Light](Compendium/Mechanics/CLI/spells/light-xphb.md) | 0 |
| [Lightning Bolt](Compendium/Mechanics/CLI/spells/lightning-bolt-xphb.md) (level 7 version) | 7 |
| [Mage Hand](Compendium/Mechanics/CLI/spells/mage-hand-xphb.md) | 0 |
| [Passwall](Compendium/Mechanics/CLI/spells/passwall-xphb.md) | 5 |
| [Plane Shift](Compendium/Mechanics/CLI/spells/plane-shift-xphb.md) | 7 |
| [Protection from Evil and Good](Compendium/Mechanics/CLI/spells/protection-from-evil-and-good-xphb.md) | 0 |
| [Telekinesis](Compendium/Mechanics/CLI/spells/telekinesis-xphb.md) | 5 |
| [Wall of Fire](Compendium/Mechanics/CLI/spells/wall-of-fire-xphb.md) | 4 |
| [Web](Compendium/Mechanics/CLI/spells/web-xphb.md) | 2 |
^spell-charge-cost

## Regaining Charges

The staff regains `4d6 + 2` expended charges daily at dawn. If you expend the last charge, roll `1d20`. On a 20, the staff regains `1d12 + 1` charges.

## Retributive Strike

You can take a [Magic](Compendium/Mechanics/CLI/Rules/actions.md#Magic) action to break the staff over your knee or against a solid surface. The staff is destroyed and releases its magic in an explosion that fills a 30-foot [Emanation](Compendium/Mechanics/CLI/Rules/variant-rules/emanation-area-of-effect-xphb.md) originating from itself. You have a 50 percent chance to instantly travel to a random plane of existence, avoiding the explosion. If you fail to avoid the effect, you take Force damage equal to 16 times the number of charges in the staff. Each other creature in the area makes a DC 17 Dexterity saving throw. On a failed save, a creature takes Force damage equal to 6 times the number of charges in the staff. On a successful save, a creature takes half as much damage.

_Source: Dungeon Master's Guide (2024) p. 310. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)_
