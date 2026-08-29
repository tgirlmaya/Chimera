---
publish: true
aliases:
  - Earthquake
created: 2026-08-28T20:41:14.555Z
modified: 2026-08-29T18:07:41.897Z
tags:
  - ttrpg-cli/compendium/src/5e/xphb
  - ttrpg-cli/spell/class/bard
  - ttrpg-cli/spell/class/cleric
  - ttrpg-cli/spell/class/druid
  - ttrpg-cli/spell/class/sorcerer
  - ttrpg-cli/spell/level/8th-level
  - ttrpg-cli/spell/school/transmutation
cssclasses:
  - json5e-spell
---

# Earthquake

_8th-level, Transmutation_

- **Casting time:** 1 Action
- **Range:** 500 feet
- **Components:** V, S, M (a fractured rock)
- **Duration:** Concentration, up to 1 minute

Choose a point on the ground that you can see within range. For the duration, an intense tremor rips through the ground in a 100-foot-radius circle centered on that point. The ground there is [Difficult Terrain](Compendium/Mechanics/CLI/Rules/variant-rules/difficult-terrain-xphb.md).

When you cast this spell and at the end of each of your turns for the duration, each creature on the ground in the area makes a Dexterity saving throw. On a failed save, a creature has the [Prone](Compendium/Mechanics/CLI/Rules/conditions.md#Prone) condition, and its [Concentration](Compendium/Mechanics/CLI/Rules/conditions.md#Concentration) is broken.

You can also cause the effects below.

## Fissures

A total of `1d6` fissures open in the spell's area at the end of the turn you cast it. You choose the fissures' locations, which can't be under structures. Each fissure is `1d10 × 10` feet deep and 10 feet wide, and it extends from one edge of the spell's area to another edge. A creature in the same space as a fissure must succeed on a Dexterity saving throw or fall in. A creature that successfully saves moves with the fissure's edge as it opens.

## Structures

The tremor deals 50 Bludgeoning damage to any structure in contact with the ground in the area when you cast the spell and at the end of each of your turns until the spell ends. If a structure drops to 0 [Hit Points](Compendium/Mechanics/CLI/Rules/variant-rules/hit-points-xphb.md), it collapses.

A creature within a distance from a collapsing structure equal to half the structure's height makes a Dexterity saving throw. On a failed save, the creature takes `12d6` Bludgeoning damage, has the [Prone](Compendium/Mechanics/CLI/Rules/conditions.md#Prone) condition, and is buried in the rubble, requiring a DC 20 Strength ([Athletics](Compendium/Mechanics/CLI/Rules/skills.md#Athletics)) check as an action to escape. On a successful save, the creature takes half as much damage only.

## Summary

**Classes**: [Bard](Compendium/Mechanics/CLI/lists/list-spells-classes-bard.md); [Cleric](Compendium/Mechanics/CLI/lists/list-spells-classes-cleric.md); [Druid](Compendium/Mechanics/CLI/lists/list-spells-classes-druid.md); [Sorcerer](Compendium/Mechanics/CLI/lists/list-spells-classes-sorcerer.md)

_Source: Player's Handbook (2024) p. 267. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)_
