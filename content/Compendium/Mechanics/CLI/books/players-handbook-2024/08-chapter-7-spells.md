---
obsidianUIMode: preview
cssclasses:
  - json5e-note
tags:
  - ttrpg-cli/compendium/src/5e/xphb
aliases:
  - "Chapter 7: Spells"
publish: true
---

# Chapter 7: Spells

_Source: Player's Handbook (2024), p. 235_

![Archmages of Greyhawk—Jallarzi, Mordenkainen, and Bigby—prepare their magic as they open a gate to another plane](Compendium/Mechanics/CLI/books/players-handbook-2024/img/181-08-001-jallarzi-mordenkainen-bigby.webp#center)

This chapter gives rules for casting spells. It also includes "descriptions" of common spells in the worlds of Dungeons & Dragons. Those spells are used by many class features, magic items, and monsters.

## Gaining Spells

Before you can cast a spell, you must have the spell prepared in your mind or have access to the spell from a magic item, such as a [Spell Scroll](Compendium/Mechanics/CLI/items/spell-scroll-xdmg.md). Your features specify which spells you have access to, if any; whether you always have certain spells prepared; and whether you can change the list of spells you have prepared.

### Preparing Spells

If you have a list of level 1+ spells you prepare, your spellcasting feature specifies when you can change the list and the number of spells you can change, as summarized in the Spell Preparation by Class table.

![Preparing Spells; Spell Preparation by Class](Compendium/Mechanics/CLI/tables/preparing-spells-spell-preparation-by-class-xphb.md)

Most spellcasting monsters don't change their lists of prepared spells, but the DM is free to alter them.

### Always-Prepared Spells

Certain features might give you a spell that you always have prepared. If you also have a list of prepared spells that you can change, a spell that you always have prepared doesn't count against the number of spells on that list.

> [!note] Casting in Armor
>
> You must have training with any armor you are wearing to cast spells while wearing it. You are otherwise too hampered by the armor for spellcasting.
> ^casting-in-armor

## Casting Spells

Each "spell description" has a series of entries that provide the details needed to cast the spell. The following sections explain each of those entries, which follow a spell's name.

### Spell Level

Every spell has a level from 0 to 9, which is indicated in a spell's description. A spell's level is an indicator of how powerful it is. Cantrips—simple spells that can be cast almost by rote—are level 0. The rules for each spellcasting class say when its members gain access to spells of certain levels.

#### Spell Slots

Spellcasting is taxing, so a spellcaster can cast only a limited number of level 1+ spells before resting. Spell slots are the main way a spellcaster's magical potential is represented. Each spellcasting class gives its members a limited number of spell slots of certain spell levels. For example, a level 3 Wizard has four level 1 spell slots and two level 2 slots.

When you cast a spell, you expend a slot of that spell's level or higher, effectively "filling" a slot with the spell. Imagine a spell slot is a groove of a certain size—small for a level 1 slot and larger for a higher-level spell. A level 1 spell fits into a slot of any size, but a level 2 spell fits only into a slot that's at least level 2. So when a level 3 Wizard casts [Magic Missile](Compendium/Mechanics/CLI/spells/magic-missile-xphb.md), a level 1 spell, that Wizard spends one of four level 1 slots and has three remaining.

Finishing a [Long Rest](Compendium/Mechanics/CLI/Rules/variant-rules/long-rest-xphb.md) restores any expended spell slots.

#### Casting without Slots

There are several ways to cast a spell without expending a spell slot:

- **Cantrips.** A cantrip is cast without a spell slot.
- **Rituals.** Certain spells have the Ritual tag in the Casting Time entry. Such a spell can be cast following the normal rules for spellcasting, or it can be cast as a Ritual. The Ritual version of a spell takes 10 minutes longer to cast than normal, but it doesn't expend a spell slot. To cast a spell as a Ritual, a spellcaster must have it prepared.
- **Special Abilities.** Some characters and monsters have special abilities that allow them to cast specific spells without a spell slot. This casting is usually limited in another way, such as being able to cast the spell a limited number of times per day.
- **Magic Items.** [Spell Scrolls](Compendium/Mechanics/CLI/items/spell-scroll-xdmg.md) and some other magic items contain spells that can be cast without a spell slot. The description of such an item specifies how many times a spell can be cast from it.

#### Using a Higher-Level Spell Slot

When a spellcaster casts a spell using a slot that is of a higher level than the spell, the spell takes on the higher level for that casting. For instance, if a Wizard casts [Magic Missile](Compendium/Mechanics/CLI/spells/magic-missile-xphb.md) using a level 2 slot, that _Magic Missile_ is level 2. Effectively, the spell expands to fill the slot it is put into.

Some spells, such as [Magic Missile](Compendium/Mechanics/CLI/spells/magic-missile-xphb.md) and [Cure Wounds](Compendium/Mechanics/CLI/spells/cure-wounds-xphb.md), have more powerful effects when cast at a higher level, as detailed in a spell's description.

### School of Magic

Each spell belongs to a school of magic. The schools are listed in the Schools of Magic table. These categories help describe spells but have no rules of their own, although some other rules refer to them.

![School of Magic; Schools of Magic](Compendium/Mechanics/CLI/tables/school-of-magic-schools-of-magic-xphb.md)

### Class Spell Lists

If a spell is on a class's spell list, the class's name appears in parentheses after the spell's school of magic. Some features add a spell to a character's spell list even if the character isn't a member of a class in the parentheses.

### Casting Time

Most spells require the [Magic](Compendium/Mechanics/CLI/Rules/actions.md#Magic) action to cast, but some spells require a Bonus Action, a Reaction, or 1 minute or more. A spell's Casting Time entry specifies which of those is required.

#### One Spell with a Spell Slot per Turn

On a turn, you can expend only one spell slot to cast a spell. This rule means you can't, for example, cast a spell with a spell slot using the [Magic](Compendium/Mechanics/CLI/Rules/actions.md#Magic) action and another one using a Bonus Action on the same turn.

#### Reaction and Bonus Action Triggers

A spell that has a casting time of a Reaction is cast in response to a trigger that is defined in the spell's Casting Time entry. Some spells that have a casting time of a Bonus Action are also cast in response to a trigger defined in the spell.

#### Longer Casting Times

Certain spells—including a spell cast as a [Ritual](Compendium/Mechanics/CLI/Rules/variant-rules/ritual-xphb.md)—require more time to cast: minutes or even hours. While you cast a spell with a casting time of 1 minute or more, you must take the [Magic](Compendium/Mechanics/CLI/Rules/actions.md#Magic) action on each of your turns, and you must maintain [Concentration](Compendium/Mechanics/CLI/Rules/conditions.md#Concentration) while you do so. If your Concentration is broken, the spell fails, but you don't expend a spell slot. To cast the spell again, you must start over.

### Range

A spell's range indicates how far from the spellcaster the spell's effect can originate, and the spell's description specifies which part of the effect is limited by the range.

A range usually takes one of the following forms:

- **Distance.** The range is expressed in feet.
- **Touch.** The spell's effect originates on something the spellcaster must touch, as defined in the spell.
- **Self.** The spell is cast on the spellcaster or emanates from them, as specified in the spell.

If a spell has movable effects, they aren't restricted by its range unless the spell's description says otherwise.

### Components

![An aasimar Wizard uses a crystal material component to focus the magic of Cone of Cold](Compendium/Mechanics/CLI/books/players-handbook-2024/img/182-08-002-aasimar-wizard.webp#center)

A spell's components are physical requirements the spellcaster must meet to cast the spell. Each spell's description indicates whether it requires Verbal (V), Somatic (S), or Material (M) components. If the spellcaster can't provide one or more of a spell's components, the spellcaster can't cast the spell.

#### Verbal (V)

A Verbal component is the chanting of esoteric words that sound like nonsense to the uninitiated. The words must be uttered in a normal speaking voice. The words themselves aren't the source of the spell's power; rather, the particular combination of sounds, with specific pitch and resonance, sets the threads of magic in motion. Thus, a creature who is gagged or in an area of magical silence can't cast a spell with a Verbal component.

> [!note] Creating Verbal Components
>
> If you'd like to say a spell's Verbal component, you may make up the words. However you make them, the goal is to create something that's easy to say and that doesn't mean anything in the real world. Consider this method: take the name of the spell, keep only one instance of each of its letters, and rearrange the remaining letters into words. For example, remove the second _l_ from [Fireball](Compendium/Mechanics/CLI/spells/fireball-xphb.md) and rearrange the remaining letters to create _Ber Fila_ or _Fel Bira_.
> ^creating-verbal-components

#### Somatic (S)

A Somatic component is a forceful gesticulation or an intricate set of gestures. A spellcaster must use at least one of their hands to perform these movements.

#### Material (M)

A Material component is a particular material used in a spell's casting, as specified in parentheses in the Components entry. These materials aren't consumed by the spell unless the spell's description states otherwise. The spellcaster must have a hand free to access them, but it can be the same hand used to perform Somatic components, if any.

If a spell doesn't consume its materials and doesn't specify a cost for them, a spellcaster can use a [Component Pouch](Compendium/Mechanics/CLI/items/component-pouch-xphb.md) (see "chapter 6") instead of providing the materials specified in the spell, or the spellcaster can substitute a [Spellcasting Focus](Compendium/Mechanics/CLI/Rules/variant-rules/spellcasting-focus-xphb.md) if the caster has a feature that allows that substitution. To use a Component Pouch, you must have a hand free to reach into it, and to use a [Spellcasting Focus](Compendium/Mechanics/CLI/Rules/variant-rules/spellcasting-focus-xphb.md), you must hold it unless its description says otherwise (see "chapter 6" for descriptions).

### Duration

A spell's duration is the length of time the spell persists after it is cast. A duration typically takes one of the following forms:

- **Concentration.** A duration that requires Concentration follows the [Concentration](Compendium/Mechanics/CLI/Rules/conditions.md#Concentration) rules.
- **Instantaneous.** An instantaneous duration means the spell's magic appears only for a moment and then disappears.
- **Time Span.** A duration that provides a time span specifies how long the spell lasts in rounds, minutes, hours, or the like. For example, a Duration entry might say "1 minute," meaning the spell ends after 1 minute has passed. While a time-span spell that you cast is ongoing, you can dismiss it (no action required) if you don't have the [Incapacitated](Compendium/Mechanics/CLI/Rules/conditions.md#Incapacitated) condition.

### Effects

The effects of a spell are detailed after its duration entry. Those details present exactly what the spell does, which ignores mundane physical laws; any outcomes beyond those effects are under the DM's purview. Whatever the effects, they typically deal with targets, saving throws, attack rolls, or all three, each of which is detailed below.

#### Targets

A typical spell requires the caster to pick one or more targets to be affected by the spell's magic. A spell's description says whether the spell targets creatures, objects, or something else.

##### A Clear Path to the Target

To target something with a spell, a caster must have a clear path to it, so it can't be behind [Total Cover](Compendium/Mechanics/CLI/Rules/variant-rules/cover-xphb.md).

##### Targeting Yourself

If a spell targets a creature of your choice, you can choose yourself unless the creature must be [Hostile](Compendium/Mechanics/CLI/Rules/variant-rules/hostile-attitude-xphb.md) or specifically a creature other than you.

##### Areas of Effect

Some spells, such as [Thunderwave](Compendium/Mechanics/CLI/spells/thunderwave-xphb.md), cover an area called an [area of effect](Compendium/Mechanics/CLI/Rules/variant-rules/area-of-effect-xphb.md), which is defined in the "rules glossary". The area determines what the spell targets. The description of a spell specifies whether it has an area of effect, which is typically one of these shapes: [Cone](Compendium/Mechanics/CLI/Rules/variant-rules/cone-area-of-effect-xphb.md), [Cube](Compendium/Mechanics/CLI/Rules/variant-rules/cube-area-of-effect-xphb.md), [Cylinder](Compendium/Mechanics/CLI/Rules/variant-rules/cylinder-area-of-effect-xphb.md), [Emanation](Compendium/Mechanics/CLI/Rules/variant-rules/emanation-area-of-effect-xphb.md), [Line](Compendium/Mechanics/CLI/Rules/variant-rules/line-area-of-effect-xphb.md), or [Sphere](Compendium/Mechanics/CLI/Rules/variant-rules/sphere-area-of-effect-xphb.md).

![](Compendium/Mechanics/CLI/books/players-handbook-2024/img/183-08-003-areas-of-effect.webp#center)

##### Awareness of Being Targeted

Unless a spell has a perceptible effect, a creature doesn't know it was targeted by the spell. An effect like lightning is obvious, but a more subtle effect, such as an attempt to read thoughts, goes unnoticed unless a spell's description says otherwise.

##### Invalid Targets

If you cast a spell on someone or something that can't be affected by it, nothing happens to that target, but if you used a spell slot to cast the spell, the slot is still expended.

If the spell normally has no effect on a target that succeeds on a saving throw, the invalid target appears to have succeeded on its saving throw, even though it didn't attempt one (giving no hint that the creature is an invalid target). Otherwise, you perceive that the spell did nothing to the target.

#### Saving Throws

Many spells specify that a target makes a saving throw to avoid some or all of a spell's effects. The spell specifies the ability that the target uses for the save and what happens on a success or failure. Here's how to calculate the DC for your spells:

<span class='abilityDc'>**Spell save DC**: Spellcasting + Proficiency Bonus</span>

#### Attack Rolls

Some spells require the caster to make an attack roll to determine whether the spell hits a target. Here's how to calculate the attack modifier for your spells:

<span class='abilityAttackMod'>**Spell attack modifier**: Spellcasting + Proficiency Bonus</span>

#### Combining Spell Effects

The effects of different spells add together while their durations overlap. In contrast, the effects of the same spell cast multiple times don't combine. Instead, the most potent effect—such as the highest bonus—from those castings applies while their durations overlap. The most recent effect applies if the castings are equally potent and their durations overlap. For example, if two Clerics cast [Bless](Compendium/Mechanics/CLI/spells/bless-xphb.md) on the same target, that target gains the spell's benefit only once; the target doesn't receive two bonus dice. But if the durations of the spells overlap, the effect continues until the duration of the second _Bless_ ends.

> [!note] Identifying an Ongoing Spell
>
> You can try to identify a non-instantaneous spell by its observable effects if its duration is ongoing. To identify it, you must take the [Study](Compendium/Mechanics/CLI/Rules/actions.md#Study) action and succeed on a DC 15 Intelligence ([Arcana](Compendium/Mechanics/CLI/Rules/skills.md#Arcana)) check.
> ^identifying-an-ongoing-spell

## Spell Descriptions

The spells are presented in alphabetical order.

- [Acid Splash](Compendium/Mechanics/CLI/spells/acid-splash-xphb.md)

- [Aid](Compendium/Mechanics/CLI/spells/aid-xphb.md)

- [Alarm](Compendium/Mechanics/CLI/spells/alarm-xphb.md)

- [Alter Self](Compendium/Mechanics/CLI/spells/alter-self-xphb.md)

- [Animal Friendship](Compendium/Mechanics/CLI/spells/animal-friendship-xphb.md)

- [Animal Messenger](Compendium/Mechanics/CLI/spells/animal-messenger-xphb.md)

- [Animal Shapes](Compendium/Mechanics/CLI/spells/animal-shapes-xphb.md)

- [Animate Dead](Compendium/Mechanics/CLI/spells/animate-dead-xphb.md)

- [Animate Objects](Compendium/Mechanics/CLI/spells/animate-objects-xphb.md)

- [Antilife Shell](Compendium/Mechanics/CLI/spells/antilife-shell-xphb.md)

- [Antimagic Field](Compendium/Mechanics/CLI/spells/antimagic-field-xphb.md)

- [Antipathy/Sympathy](Compendium/Mechanics/CLI/spells/antipathy-sympathy-xphb.md)

- [Arcane Eye](Compendium/Mechanics/CLI/spells/arcane-eye-xphb.md)

- [Arcane Gate](Compendium/Mechanics/CLI/spells/arcane-gate-xphb.md)

- [Arcane Lock](Compendium/Mechanics/CLI/spells/arcane-lock-xphb.md)

- [Arcane Vigor](Compendium/Mechanics/CLI/spells/arcane-vigor-xphb.md)

- [Armor of Agathys](Compendium/Mechanics/CLI/spells/armor-of-agathys-xphb.md)

- [Arms of Hadar](Compendium/Mechanics/CLI/spells/arms-of-hadar-xphb.md)

- [Astral Projection](Compendium/Mechanics/CLI/spells/astral-projection-xphb.md)

- [Augury](Compendium/Mechanics/CLI/spells/augury-xphb.md)

- [Aura of Life](Compendium/Mechanics/CLI/spells/aura-of-life-xphb.md)

- [Aura of Purity](Compendium/Mechanics/CLI/spells/aura-of-purity-xphb.md)

- [Aura of Vitality](Compendium/Mechanics/CLI/spells/aura-of-vitality-xphb.md)

- [Awaken](Compendium/Mechanics/CLI/spells/awaken-xphb.md)

- [Bane](Compendium/Mechanics/CLI/spells/bane-xphb.md)

- [Banishing Smite](Compendium/Mechanics/CLI/spells/banishing-smite-xphb.md)

- [Banishment](Compendium/Mechanics/CLI/spells/banishment-xphb.md)

- [Barkskin](Compendium/Mechanics/CLI/spells/barkskin-xphb.md)

- [Beacon of Hope](Compendium/Mechanics/CLI/spells/beacon-of-hope-xphb.md)

- [Beast Sense](Compendium/Mechanics/CLI/spells/beast-sense-xphb.md)

- [Befuddlement](Compendium/Mechanics/CLI/spells/befuddlement-xphb.md)

- [Bestow Curse](Compendium/Mechanics/CLI/spells/bestow-curse-xphb.md)

- [Bigby's Hand](Compendium/Mechanics/CLI/spells/bigbys-hand-xphb.md)

- [Blade Barrier](Compendium/Mechanics/CLI/spells/blade-barrier-xphb.md)

- [Blade Ward](Compendium/Mechanics/CLI/spells/blade-ward-xphb.md)

- [Bless](Compendium/Mechanics/CLI/spells/bless-xphb.md)

- [Blight](Compendium/Mechanics/CLI/spells/blight-xphb.md)

- [Blinding Smite](Compendium/Mechanics/CLI/spells/blinding-smite-xphb.md)

- [Blindness/Deafness](Compendium/Mechanics/CLI/spells/blindness-deafness-xphb.md)

- [Blink](Compendium/Mechanics/CLI/spells/blink-xphb.md)

- [Blur](Compendium/Mechanics/CLI/spells/blur-xphb.md)

- [Burning Hands](Compendium/Mechanics/CLI/spells/burning-hands-xphb.md)

- [Call Lightning](Compendium/Mechanics/CLI/spells/call-lightning-xphb.md)

- [Calm Emotions](Compendium/Mechanics/CLI/spells/calm-emotions-xphb.md)

- [Chain Lightning](Compendium/Mechanics/CLI/spells/chain-lightning-xphb.md)

- [Charm Monster](Compendium/Mechanics/CLI/spells/charm-monster-xphb.md)

- [Charm Person](Compendium/Mechanics/CLI/spells/charm-person-xphb.md)

- [Chill Touch](Compendium/Mechanics/CLI/spells/chill-touch-xphb.md)

- [Chromatic Orb](Compendium/Mechanics/CLI/spells/chromatic-orb-xphb.md)

- [Circle of Death](Compendium/Mechanics/CLI/spells/circle-of-death-xphb.md)

- [Circle of Power](Compendium/Mechanics/CLI/spells/circle-of-power-xphb.md)

- [Clairvoyance](Compendium/Mechanics/CLI/spells/clairvoyance-xphb.md)

- [Clone](Compendium/Mechanics/CLI/spells/clone-xphb.md)

- [Cloud of Daggers](Compendium/Mechanics/CLI/spells/cloud-of-daggers-xphb.md)

- [Cloudkill](Compendium/Mechanics/CLI/spells/cloudkill-xphb.md)

- [Color Spray](Compendium/Mechanics/CLI/spells/color-spray-xphb.md)

- [Command](Compendium/Mechanics/CLI/spells/command-xphb.md)

- [Commune](Compendium/Mechanics/CLI/spells/commune-xphb.md)

- [Commune with Nature](Compendium/Mechanics/CLI/spells/commune-with-nature-xphb.md)

- [Compelled Duel](Compendium/Mechanics/CLI/spells/compelled-duel-xphb.md)

- [Comprehend Languages](Compendium/Mechanics/CLI/spells/comprehend-languages-xphb.md)

- [Compulsion](Compendium/Mechanics/CLI/spells/compulsion-xphb.md)

- [Cone of Cold](Compendium/Mechanics/CLI/spells/cone-of-cold-xphb.md)

- [Confusion](Compendium/Mechanics/CLI/spells/confusion-xphb.md)

- [Conjure Animals](Compendium/Mechanics/CLI/spells/conjure-animals-xphb.md)

- [Conjure Barrage](Compendium/Mechanics/CLI/spells/conjure-barrage-xphb.md)

- [Conjure Celestial](Compendium/Mechanics/CLI/spells/conjure-celestial-xphb.md)

- [Conjure Elemental](Compendium/Mechanics/CLI/spells/conjure-elemental-xphb.md)

- [Conjure Fey](Compendium/Mechanics/CLI/spells/conjure-fey-xphb.md)

- [Conjure Minor Elementals](Compendium/Mechanics/CLI/spells/conjure-minor-elementals-xphb.md)

- [Conjure Volley](Compendium/Mechanics/CLI/spells/conjure-volley-xphb.md)

- [Conjure Woodland Beings](Compendium/Mechanics/CLI/spells/conjure-woodland-beings-xphb.md)

- [Contact Other Plane](Compendium/Mechanics/CLI/spells/contact-other-plane-xphb.md)

- [Contagion](Compendium/Mechanics/CLI/spells/contagion-xphb.md)

- [Contingency](Compendium/Mechanics/CLI/spells/contingency-xphb.md)

- [Continual Flame](Compendium/Mechanics/CLI/spells/continual-flame-xphb.md)

- [Control Water](Compendium/Mechanics/CLI/spells/control-water-xphb.md)

- [Control Weather](Compendium/Mechanics/CLI/spells/control-weather-xphb.md)

- [Cordon of Arrows](Compendium/Mechanics/CLI/spells/cordon-of-arrows-xphb.md)

- [Counterspell](Compendium/Mechanics/CLI/spells/counterspell-xphb.md)

- [Create Food and Water](Compendium/Mechanics/CLI/spells/create-food-and-water-xphb.md)

- [Create or Destroy Water](Compendium/Mechanics/CLI/spells/create-or-destroy-water-xphb.md)

- [Create Undead](Compendium/Mechanics/CLI/spells/create-undead-xphb.md)

- [Creation](Compendium/Mechanics/CLI/spells/creation-xphb.md)

- [Crown of Madness](Compendium/Mechanics/CLI/spells/crown-of-madness-xphb.md)

- [Crusader's Mantle](Compendium/Mechanics/CLI/spells/crusaders-mantle-xphb.md)

- [Cure Wounds](Compendium/Mechanics/CLI/spells/cure-wounds-xphb.md)

- [Dancing Lights](Compendium/Mechanics/CLI/spells/dancing-lights-xphb.md)

- [Darkness](Compendium/Mechanics/CLI/spells/darkness-xphb.md)

- [Darkvision](Compendium/Mechanics/CLI/spells/darkvision-xphb.md)

- [Daylight](Compendium/Mechanics/CLI/spells/daylight-xphb.md)

- [Death Ward](Compendium/Mechanics/CLI/spells/death-ward-xphb.md)

- [Delayed Blast Fireball](Compendium/Mechanics/CLI/spells/delayed-blast-fireball-xphb.md)

- [Demiplane](Compendium/Mechanics/CLI/spells/demiplane-xphb.md)

- [Destructive Wave](Compendium/Mechanics/CLI/spells/destructive-wave-xphb.md)

- [Detect Evil and Good](Compendium/Mechanics/CLI/spells/detect-evil-and-good-xphb.md)

- [Detect Magic](Compendium/Mechanics/CLI/spells/detect-magic-xphb.md)

- [Detect Poison and Disease](Compendium/Mechanics/CLI/spells/detect-poison-and-disease-xphb.md)

- [Detect Thoughts](Compendium/Mechanics/CLI/spells/detect-thoughts-xphb.md)

- [Dimension Door](Compendium/Mechanics/CLI/spells/dimension-door-xphb.md)

- [Disguise Self](Compendium/Mechanics/CLI/spells/disguise-self-xphb.md)

- [Disintegrate](Compendium/Mechanics/CLI/spells/disintegrate-xphb.md)

- [Dispel Evil and Good](Compendium/Mechanics/CLI/spells/dispel-evil-and-good-xphb.md)

- [Dispel Magic](Compendium/Mechanics/CLI/spells/dispel-magic-xphb.md)

- [Dissonant Whispers](Compendium/Mechanics/CLI/spells/dissonant-whispers-xphb.md)

- [Divination](Compendium/Mechanics/CLI/spells/divination-xphb.md)

- [Divine Favor](Compendium/Mechanics/CLI/spells/divine-favor-xphb.md)

- [Divine Smite](Compendium/Mechanics/CLI/spells/divine-smite-xphb.md)

- [Divine Word](Compendium/Mechanics/CLI/spells/divine-word-xphb.md)

- [Dominate Beast](Compendium/Mechanics/CLI/spells/dominate-beast-xphb.md)

- [Dominate Monster](Compendium/Mechanics/CLI/spells/dominate-monster-xphb.md)

- [Dominate Person](Compendium/Mechanics/CLI/spells/dominate-person-xphb.md)

- [Dragon's Breath](Compendium/Mechanics/CLI/spells/dragons-breath-xphb.md)

- [Drawmij's Instant Summons](Compendium/Mechanics/CLI/spells/drawmijs-instant-summons-xphb.md)

- [Dream](Compendium/Mechanics/CLI/spells/dream-xphb.md)

- [Druidcraft](Compendium/Mechanics/CLI/spells/druidcraft-xphb.md)

- [Earthquake](Compendium/Mechanics/CLI/spells/earthquake-xphb.md)

- [Eldritch Blast](Compendium/Mechanics/CLI/spells/eldritch-blast-xphb.md)

- [Elemental Weapon](Compendium/Mechanics/CLI/spells/elemental-weapon-xphb.md)

- [Elementalism](Compendium/Mechanics/CLI/spells/elementalism-xphb.md)

- [Enhance Ability](Compendium/Mechanics/CLI/spells/enhance-ability-xphb.md)

- [Enlarge/Reduce](Compendium/Mechanics/CLI/spells/enlarge-reduce-xphb.md)

- [Ensnaring Strike](Compendium/Mechanics/CLI/spells/ensnaring-strike-xphb.md)

- [Entangle](Compendium/Mechanics/CLI/spells/entangle-xphb.md)

- [Enthrall](Compendium/Mechanics/CLI/spells/enthrall-xphb.md)

- [Etherealness](Compendium/Mechanics/CLI/spells/etherealness-xphb.md)

- [Evard's Black Tentacles](Compendium/Mechanics/CLI/spells/evards-black-tentacles-xphb.md)

- [Expeditious Retreat](Compendium/Mechanics/CLI/spells/expeditious-retreat-xphb.md)

- [Eyebite](Compendium/Mechanics/CLI/spells/eyebite-xphb.md)

- [Fabricate](Compendium/Mechanics/CLI/spells/fabricate-xphb.md)

- [Faerie Fire](Compendium/Mechanics/CLI/spells/faerie-fire-xphb.md)

- [False Life](Compendium/Mechanics/CLI/spells/false-life-xphb.md)

- [Fear](Compendium/Mechanics/CLI/spells/fear-xphb.md)

- [Feather Fall](Compendium/Mechanics/CLI/spells/feather-fall-xphb.md)

- [Feign Death](Compendium/Mechanics/CLI/spells/feign-death-xphb.md)

- [Find Familiar](Compendium/Mechanics/CLI/spells/find-familiar-xphb.md)

- [Find Steed](Compendium/Mechanics/CLI/spells/find-steed-xphb.md)

- [Find the Path](Compendium/Mechanics/CLI/spells/find-the-path-xphb.md)

- [Find Traps](Compendium/Mechanics/CLI/spells/find-traps-xphb.md)

- [Finger of Death](Compendium/Mechanics/CLI/spells/finger-of-death-xphb.md)

- [Fire Bolt](Compendium/Mechanics/CLI/spells/fire-bolt-xphb.md)

- [Fire Shield](Compendium/Mechanics/CLI/spells/fire-shield-xphb.md)

- [Fire Storm](Compendium/Mechanics/CLI/spells/fire-storm-xphb.md)

- [Fireball](Compendium/Mechanics/CLI/spells/fireball-xphb.md)

- [Flame Blade](Compendium/Mechanics/CLI/spells/flame-blade-xphb.md)

- [Flame Strike](Compendium/Mechanics/CLI/spells/flame-strike-xphb.md)

- [Flaming Sphere](Compendium/Mechanics/CLI/spells/flaming-sphere-xphb.md)

- [Flesh to Stone](Compendium/Mechanics/CLI/spells/flesh-to-stone-xphb.md)

- [Fly](Compendium/Mechanics/CLI/spells/fly-xphb.md)

- [Fog Cloud](Compendium/Mechanics/CLI/spells/fog-cloud-xphb.md)

- [Forbiddance](Compendium/Mechanics/CLI/spells/forbiddance-xphb.md)

- [Forcecage](Compendium/Mechanics/CLI/spells/forcecage-xphb.md)

- [Foresight](Compendium/Mechanics/CLI/spells/foresight-xphb.md)

- [Fount of Moonlight](Compendium/Mechanics/CLI/spells/fount-of-moonlight-xphb.md)

- [Freedom of Movement](Compendium/Mechanics/CLI/spells/freedom-of-movement-xphb.md)

- [Friends](Compendium/Mechanics/CLI/spells/friends-xphb.md)

- [Gaseous Form](Compendium/Mechanics/CLI/spells/gaseous-form-xphb.md)

- [Gate](Compendium/Mechanics/CLI/spells/gate-xphb.md)

- [Geas](Compendium/Mechanics/CLI/spells/geas-xphb.md)

- [Gentle Repose](Compendium/Mechanics/CLI/spells/gentle-repose-xphb.md)

- [Giant Insect](Compendium/Mechanics/CLI/spells/giant-insect-xphb.md)

- [Glibness](Compendium/Mechanics/CLI/spells/glibness-xphb.md)

- [Globe of Invulnerability](Compendium/Mechanics/CLI/spells/globe-of-invulnerability-xphb.md)

- [Glyph of Warding](Compendium/Mechanics/CLI/spells/glyph-of-warding-xphb.md)

- [Goodberry](Compendium/Mechanics/CLI/spells/goodberry-xphb.md)

- [Grasping Vine](Compendium/Mechanics/CLI/spells/grasping-vine-xphb.md)

- [Grease](Compendium/Mechanics/CLI/spells/grease-xphb.md)

- [Greater Invisibility](Compendium/Mechanics/CLI/spells/greater-invisibility-xphb.md)

- [Greater Restoration](Compendium/Mechanics/CLI/spells/greater-restoration-xphb.md)

- [Guardian of Faith](Compendium/Mechanics/CLI/spells/guardian-of-faith-xphb.md)

- [Guards and Wards](Compendium/Mechanics/CLI/spells/guards-and-wards-xphb.md)

- [Guidance](Compendium/Mechanics/CLI/spells/guidance-xphb.md)

- [Guiding Bolt](Compendium/Mechanics/CLI/spells/guiding-bolt-xphb.md)

- [Gust of Wind](Compendium/Mechanics/CLI/spells/gust-of-wind-xphb.md)

- [Hail of Thorns](Compendium/Mechanics/CLI/spells/hail-of-thorns-xphb.md)

- [Hallow](Compendium/Mechanics/CLI/spells/hallow-xphb.md)

- [Hallucinatory Terrain](Compendium/Mechanics/CLI/spells/hallucinatory-terrain-xphb.md)

- [Harm](Compendium/Mechanics/CLI/spells/harm-xphb.md)

- [Haste](Compendium/Mechanics/CLI/spells/haste-xphb.md)

- [Heal](Compendium/Mechanics/CLI/spells/heal-xphb.md)

- [Healing Word](Compendium/Mechanics/CLI/spells/healing-word-xphb.md)

- [Heat Metal](Compendium/Mechanics/CLI/spells/heat-metal-xphb.md)

- [Hellish Rebuke](Compendium/Mechanics/CLI/spells/hellish-rebuke-xphb.md)

- [Heroes' Feast](Compendium/Mechanics/CLI/spells/heroes-feast-xphb.md)

- [Heroism](Compendium/Mechanics/CLI/spells/heroism-xphb.md)

- [Hex](Compendium/Mechanics/CLI/spells/hex-xphb.md)

- [Hold Monster](Compendium/Mechanics/CLI/spells/hold-monster-xphb.md)

- [Hold Person](Compendium/Mechanics/CLI/spells/hold-person-xphb.md)

- [Holy Aura](Compendium/Mechanics/CLI/spells/holy-aura-xphb.md)

- [Hunger of Hadar](Compendium/Mechanics/CLI/spells/hunger-of-hadar-xphb.md)

- [Hunter's Mark](Compendium/Mechanics/CLI/spells/hunters-mark-xphb.md)

- [Hypnotic Pattern](Compendium/Mechanics/CLI/spells/hypnotic-pattern-xphb.md)

- [Ice Knife](Compendium/Mechanics/CLI/spells/ice-knife-xphb.md)

- [Ice Storm](Compendium/Mechanics/CLI/spells/ice-storm-xphb.md)

- [Identify](Compendium/Mechanics/CLI/spells/identify-xphb.md)

- [Illusory Script](Compendium/Mechanics/CLI/spells/illusory-script-xphb.md)

- [Imprisonment](Compendium/Mechanics/CLI/spells/imprisonment-xphb.md)

- [Incendiary Cloud](Compendium/Mechanics/CLI/spells/incendiary-cloud-xphb.md)

- [Inflict Wounds](Compendium/Mechanics/CLI/spells/inflict-wounds-xphb.md)

- [Insect Plague](Compendium/Mechanics/CLI/spells/insect-plague-xphb.md)

- [Invisibility](Compendium/Mechanics/CLI/spells/invisibility-xphb.md)

- [Jallarzi's Storm of Radiance](Compendium/Mechanics/CLI/spells/jallarzis-storm-of-radiance-xphb.md)

- [Jump](Compendium/Mechanics/CLI/spells/jump-xphb.md)

- [Knock](Compendium/Mechanics/CLI/spells/knock-xphb.md)

- [Legend Lore](Compendium/Mechanics/CLI/spells/legend-lore-xphb.md)

- [Leomund's Secret Chest](Compendium/Mechanics/CLI/spells/leomunds-secret-chest-xphb.md)

- [Leomund's Tiny Hut](Compendium/Mechanics/CLI/spells/leomunds-tiny-hut-xphb.md)

- [Lesser Restoration](Compendium/Mechanics/CLI/spells/lesser-restoration-xphb.md)

- [Levitate](Compendium/Mechanics/CLI/spells/levitate-xphb.md)

- [Light](Compendium/Mechanics/CLI/spells/light-xphb.md)

- [Lightning Arrow](Compendium/Mechanics/CLI/spells/lightning-arrow-xphb.md)

- [Lightning Bolt](Compendium/Mechanics/CLI/spells/lightning-bolt-xphb.md)

- [Locate Animals or Plants](Compendium/Mechanics/CLI/spells/locate-animals-or-plants-xphb.md)

- [Locate Creature](Compendium/Mechanics/CLI/spells/locate-creature-xphb.md)

- [Locate Object](Compendium/Mechanics/CLI/spells/locate-object-xphb.md)

- [Longstrider](Compendium/Mechanics/CLI/spells/longstrider-xphb.md)

- [Mage Armor](Compendium/Mechanics/CLI/spells/mage-armor-xphb.md)

- [Mage Hand](Compendium/Mechanics/CLI/spells/mage-hand-xphb.md)

- [Magic Circle](Compendium/Mechanics/CLI/spells/magic-circle-xphb.md)

- [Magic Jar](Compendium/Mechanics/CLI/spells/magic-jar-xphb.md)

- [Magic Missile](Compendium/Mechanics/CLI/spells/magic-missile-xphb.md)

- [Magic Mouth](Compendium/Mechanics/CLI/spells/magic-mouth-xphb.md)

- [Magic Weapon](Compendium/Mechanics/CLI/spells/magic-weapon-xphb.md)

- [Major Image](Compendium/Mechanics/CLI/spells/major-image-xphb.md)

- [Mass Cure Wounds](Compendium/Mechanics/CLI/spells/mass-cure-wounds-xphb.md)

- [Mass Heal](Compendium/Mechanics/CLI/spells/mass-heal-xphb.md)

- [Mass Healing Word](Compendium/Mechanics/CLI/spells/mass-healing-word-xphb.md)

- [Mass Suggestion](Compendium/Mechanics/CLI/spells/mass-suggestion-xphb.md)

- [Maze](Compendium/Mechanics/CLI/spells/maze-xphb.md)

- [Meld into Stone](Compendium/Mechanics/CLI/spells/meld-into-stone-xphb.md)

- [Melf's Acid Arrow](Compendium/Mechanics/CLI/spells/melfs-acid-arrow-xphb.md)

- [Mending](Compendium/Mechanics/CLI/spells/mending-xphb.md)

- [Message](Compendium/Mechanics/CLI/spells/message-xphb.md)

- [Meteor Swarm](Compendium/Mechanics/CLI/spells/meteor-swarm-xphb.md)

- [Mind Blank](Compendium/Mechanics/CLI/spells/mind-blank-xphb.md)

- [Mind Sliver](Compendium/Mechanics/CLI/spells/mind-sliver-xphb.md)

- [Mind Spike](Compendium/Mechanics/CLI/spells/mind-spike-xphb.md)

- [Minor Illusion](Compendium/Mechanics/CLI/spells/minor-illusion-xphb.md)

- [Mirage Arcane](Compendium/Mechanics/CLI/spells/mirage-arcane-xphb.md)

- [Mirror Image](Compendium/Mechanics/CLI/spells/mirror-image-xphb.md)

- [Mislead](Compendium/Mechanics/CLI/spells/mislead-xphb.md)

- [Misty Step](Compendium/Mechanics/CLI/spells/misty-step-xphb.md)

- [Modify Memory](Compendium/Mechanics/CLI/spells/modify-memory-xphb.md)

- [Moonbeam](Compendium/Mechanics/CLI/spells/moonbeam-xphb.md)

- [Mordenkainen's Faithful Hound](Compendium/Mechanics/CLI/spells/mordenkainens-faithful-hound-xphb.md)

- [Mordenkainen's Magnificent Mansion](Compendium/Mechanics/CLI/spells/mordenkainens-magnificent-mansion-xphb.md)

- [Mordenkainen's Private Sanctum](Compendium/Mechanics/CLI/spells/mordenkainens-private-sanctum-xphb.md)

- [Mordenkainen's Sword](Compendium/Mechanics/CLI/spells/mordenkainens-sword-xphb.md)

- [Move Earth](Compendium/Mechanics/CLI/spells/move-earth-xphb.md)

- [Nondetection](Compendium/Mechanics/CLI/spells/nondetection-xphb.md)

- [Nystul's Magic Aura](Compendium/Mechanics/CLI/spells/nystuls-magic-aura-xphb.md)

- [Otiluke's Freezing Sphere](Compendium/Mechanics/CLI/spells/otilukes-freezing-sphere-xphb.md)

- [Otiluke's Resilient Sphere](Compendium/Mechanics/CLI/spells/otilukes-resilient-sphere-xphb.md)

- [Otto's Irresistible Dance](Compendium/Mechanics/CLI/spells/ottos-irresistible-dance-xphb.md)

- [Pass without Trace](Compendium/Mechanics/CLI/spells/pass-without-trace-xphb.md)

- [Passwall](Compendium/Mechanics/CLI/spells/passwall-xphb.md)

- [Phantasmal Force](Compendium/Mechanics/CLI/spells/phantasmal-force-xphb.md)

- [Phantasmal Killer](Compendium/Mechanics/CLI/spells/phantasmal-killer-xphb.md)

- [Phantom Steed](Compendium/Mechanics/CLI/spells/phantom-steed-xphb.md)

- [Planar Ally](Compendium/Mechanics/CLI/spells/planar-ally-xphb.md)

- [Planar Binding](Compendium/Mechanics/CLI/spells/planar-binding-xphb.md)

- [Plane Shift](Compendium/Mechanics/CLI/spells/plane-shift-xphb.md)

- [Plant Growth](Compendium/Mechanics/CLI/spells/plant-growth-xphb.md)

- [Poison Spray](Compendium/Mechanics/CLI/spells/poison-spray-xphb.md)

- [Polymorph](Compendium/Mechanics/CLI/spells/polymorph-xphb.md)

- [Power Word Fortify](Compendium/Mechanics/CLI/spells/power-word-fortify-xphb.md)

- [Power Word Heal](Compendium/Mechanics/CLI/spells/power-word-heal-xphb.md)

- [Power Word Kill](Compendium/Mechanics/CLI/spells/power-word-kill-xphb.md)

- [Power Word Stun](Compendium/Mechanics/CLI/spells/power-word-stun-xphb.md)

- [Prayer of Healing](Compendium/Mechanics/CLI/spells/prayer-of-healing-xphb.md)

- [Prestidigitation](Compendium/Mechanics/CLI/spells/prestidigitation-xphb.md)

- [Prismatic Spray](Compendium/Mechanics/CLI/spells/prismatic-spray-xphb.md)

- [Prismatic Wall](Compendium/Mechanics/CLI/spells/prismatic-wall-xphb.md)

- [Produce Flame](Compendium/Mechanics/CLI/spells/produce-flame-xphb.md)

- [Programmed Illusion](Compendium/Mechanics/CLI/spells/programmed-illusion-xphb.md)

- [Project Image](Compendium/Mechanics/CLI/spells/project-image-xphb.md)

- [Protection from Energy](Compendium/Mechanics/CLI/spells/protection-from-energy-xphb.md)

- [Protection from Evil and Good](Compendium/Mechanics/CLI/spells/protection-from-evil-and-good-xphb.md)

- [Protection from Poison](Compendium/Mechanics/CLI/spells/protection-from-poison-xphb.md)

- [Purify Food and Drink](Compendium/Mechanics/CLI/spells/purify-food-and-drink-xphb.md)

- [Raise Dead](Compendium/Mechanics/CLI/spells/raise-dead-xphb.md)

- [Rary's Telepathic Bond](Compendium/Mechanics/CLI/spells/rarys-telepathic-bond-xphb.md)

- [Ray of Enfeeblement](Compendium/Mechanics/CLI/spells/ray-of-enfeeblement-xphb.md)

- [Ray of Frost](Compendium/Mechanics/CLI/spells/ray-of-frost-xphb.md)

- [Ray of Sickness](Compendium/Mechanics/CLI/spells/ray-of-sickness-xphb.md)

- [Regenerate](Compendium/Mechanics/CLI/spells/regenerate-xphb.md)

- [Reincarnate](Compendium/Mechanics/CLI/spells/reincarnate-xphb.md)

- [Remove Curse](Compendium/Mechanics/CLI/spells/remove-curse-xphb.md)

- [Resistance](Compendium/Mechanics/CLI/spells/resistance-xphb.md)

- [Resurrection](Compendium/Mechanics/CLI/spells/resurrection-xphb.md)

- [Reverse Gravity](Compendium/Mechanics/CLI/spells/reverse-gravity-xphb.md)

- [Revivify](Compendium/Mechanics/CLI/spells/revivify-xphb.md)

- [Rope Trick](Compendium/Mechanics/CLI/spells/rope-trick-xphb.md)

- [Sacred Flame](Compendium/Mechanics/CLI/spells/sacred-flame-xphb.md)

- [Sanctuary](Compendium/Mechanics/CLI/spells/sanctuary-xphb.md)

- [Scorching Ray](Compendium/Mechanics/CLI/spells/scorching-ray-xphb.md)

- [Scrying](Compendium/Mechanics/CLI/spells/scrying-xphb.md)

- [Searing Smite](Compendium/Mechanics/CLI/spells/searing-smite-xphb.md)

- [See Invisibility](Compendium/Mechanics/CLI/spells/see-invisibility-xphb.md)

- [Seeming](Compendium/Mechanics/CLI/spells/seeming-xphb.md)

- [Sending](Compendium/Mechanics/CLI/spells/sending-xphb.md)

- [Sequester](Compendium/Mechanics/CLI/spells/sequester-xphb.md)

- [Shapechange](Compendium/Mechanics/CLI/spells/shapechange-xphb.md)

- [Shatter](Compendium/Mechanics/CLI/spells/shatter-xphb.md)

- [Shield](Compendium/Mechanics/CLI/spells/shield-xphb.md)

- [Shield of Faith](Compendium/Mechanics/CLI/spells/shield-of-faith-xphb.md)

- [Shillelagh](Compendium/Mechanics/CLI/spells/shillelagh-xphb.md)

- [Shining Smite](Compendium/Mechanics/CLI/spells/shining-smite-xphb.md)

- [Shocking Grasp](Compendium/Mechanics/CLI/spells/shocking-grasp-xphb.md)

- [Silence](Compendium/Mechanics/CLI/spells/silence-xphb.md)

- [Silent Image](Compendium/Mechanics/CLI/spells/silent-image-xphb.md)

- [Simulacrum](Compendium/Mechanics/CLI/spells/simulacrum-xphb.md)

- [Sleep](Compendium/Mechanics/CLI/spells/sleep-xphb.md)

- [Sleet Storm](Compendium/Mechanics/CLI/spells/sleet-storm-xphb.md)

- [Slow](Compendium/Mechanics/CLI/spells/slow-xphb.md)

- [Sorcerous Burst](Compendium/Mechanics/CLI/spells/sorcerous-burst-xphb.md)

- [Spare the Dying](Compendium/Mechanics/CLI/spells/spare-the-dying-xphb.md)

- [Speak with Animals](Compendium/Mechanics/CLI/spells/speak-with-animals-xphb.md)

- [Speak with Dead](Compendium/Mechanics/CLI/spells/speak-with-dead-xphb.md)

- [Speak with Plants](Compendium/Mechanics/CLI/spells/speak-with-plants-xphb.md)

- [Spider Climb](Compendium/Mechanics/CLI/spells/spider-climb-xphb.md)

- [Spike Growth](Compendium/Mechanics/CLI/spells/spike-growth-xphb.md)

- [Spirit Guardians](Compendium/Mechanics/CLI/spells/spirit-guardians-xphb.md)

- [Spiritual Weapon](Compendium/Mechanics/CLI/spells/spiritual-weapon-xphb.md)

- [Staggering Smite](Compendium/Mechanics/CLI/spells/staggering-smite-xphb.md)

- [Starry Wisp](Compendium/Mechanics/CLI/spells/starry-wisp-xphb.md)

- [Steel Wind Strike](Compendium/Mechanics/CLI/spells/steel-wind-strike-xphb.md)

- [Stinking Cloud](Compendium/Mechanics/CLI/spells/stinking-cloud-xphb.md)

- [Stone Shape](Compendium/Mechanics/CLI/spells/stone-shape-xphb.md)

- [Stoneskin](Compendium/Mechanics/CLI/spells/stoneskin-xphb.md)

- [Storm of Vengeance](Compendium/Mechanics/CLI/spells/storm-of-vengeance-xphb.md)

- [Suggestion](Compendium/Mechanics/CLI/spells/suggestion-xphb.md)

- [Summon Aberration](Compendium/Mechanics/CLI/spells/summon-aberration-xphb.md)

- [Summon Beast](Compendium/Mechanics/CLI/spells/summon-beast-xphb.md)

- [Summon Celestial](Compendium/Mechanics/CLI/spells/summon-celestial-xphb.md)

- [Summon Construct](Compendium/Mechanics/CLI/spells/summon-construct-xphb.md)

- [Summon Dragon](Compendium/Mechanics/CLI/spells/summon-dragon-xphb.md)

- [Summon Elemental](Compendium/Mechanics/CLI/spells/summon-elemental-xphb.md)

- [Summon Fey](Compendium/Mechanics/CLI/spells/summon-fey-xphb.md)

- [Summon Fiend](Compendium/Mechanics/CLI/spells/summon-fiend-xphb.md)

- [Summon Undead](Compendium/Mechanics/CLI/spells/summon-undead-xphb.md)

- [Sunbeam](Compendium/Mechanics/CLI/spells/sunbeam-xphb.md)

- [Sunburst](Compendium/Mechanics/CLI/spells/sunburst-xphb.md)

- [Swift Quiver](Compendium/Mechanics/CLI/spells/swift-quiver-xphb.md)

- [Symbol](Compendium/Mechanics/CLI/spells/symbol-xphb.md)

- [Synaptic Static](Compendium/Mechanics/CLI/spells/synaptic-static-xphb.md)

- [Tasha's Bubbling Cauldron](Compendium/Mechanics/CLI/spells/tashas-bubbling-cauldron-xphb.md)

- [Tasha's Hideous Laughter](Compendium/Mechanics/CLI/spells/tashas-hideous-laughter-xphb.md)

- [Telekinesis](Compendium/Mechanics/CLI/spells/telekinesis-xphb.md)

- [Telepathy](Compendium/Mechanics/CLI/spells/telepathy-xphb.md)

- [Teleport](Compendium/Mechanics/CLI/spells/teleport-xphb.md)

- [Teleportation Circle](Compendium/Mechanics/CLI/spells/teleportation-circle-xphb.md)

- [Tenser's Floating Disk](Compendium/Mechanics/CLI/spells/tensers-floating-disk-xphb.md)

- [Thaumaturgy](Compendium/Mechanics/CLI/spells/thaumaturgy-xphb.md)

- [Thorn Whip](Compendium/Mechanics/CLI/spells/thorn-whip-xphb.md)

- [Thunderclap](Compendium/Mechanics/CLI/spells/thunderclap-xphb.md)

- [Thunderous Smite](Compendium/Mechanics/CLI/spells/thunderous-smite-xphb.md)

- [Thunderwave](Compendium/Mechanics/CLI/spells/thunderwave-xphb.md)

- [Time Stop](Compendium/Mechanics/CLI/spells/time-stop-xphb.md)

- [Toll the Dead](Compendium/Mechanics/CLI/spells/toll-the-dead-xphb.md)

- [Tongues](Compendium/Mechanics/CLI/spells/tongues-xphb.md)

- [Transport via Plants](Compendium/Mechanics/CLI/spells/transport-via-plants-xphb.md)

- [Tree Stride](Compendium/Mechanics/CLI/spells/tree-stride-xphb.md)

- [True Polymorph](Compendium/Mechanics/CLI/spells/true-polymorph-xphb.md)

- [True Resurrection](Compendium/Mechanics/CLI/spells/true-resurrection-xphb.md)

- [True Seeing](Compendium/Mechanics/CLI/spells/true-seeing-xphb.md)

- [True Strike](Compendium/Mechanics/CLI/spells/true-strike-xphb.md)

- [Tsunami](Compendium/Mechanics/CLI/spells/tsunami-xphb.md)

- [Unseen Servant](Compendium/Mechanics/CLI/spells/unseen-servant-xphb.md)

- [Vampiric Touch](Compendium/Mechanics/CLI/spells/vampiric-touch-xphb.md)

- [Vicious Mockery](Compendium/Mechanics/CLI/spells/vicious-mockery-xphb.md)

- [Vitriolic Sphere](Compendium/Mechanics/CLI/spells/vitriolic-sphere-xphb.md)

- [Wall of Fire](Compendium/Mechanics/CLI/spells/wall-of-fire-xphb.md)

- [Wall of Force](Compendium/Mechanics/CLI/spells/wall-of-force-xphb.md)

- [Wall of Ice](Compendium/Mechanics/CLI/spells/wall-of-ice-xphb.md)

- [Wall of Stone](Compendium/Mechanics/CLI/spells/wall-of-stone-xphb.md)

- [Wall of Thorns](Compendium/Mechanics/CLI/spells/wall-of-thorns-xphb.md)

- [Warding Bond](Compendium/Mechanics/CLI/spells/warding-bond-xphb.md)

- [Water Breathing](Compendium/Mechanics/CLI/spells/water-breathing-xphb.md)

- [Water Walk](Compendium/Mechanics/CLI/spells/water-walk-xphb.md)

- [Web](Compendium/Mechanics/CLI/spells/web-xphb.md)

- [Weird](Compendium/Mechanics/CLI/spells/weird-xphb.md)

- [Wind Walk](Compendium/Mechanics/CLI/spells/wind-walk-xphb.md)

- [Wind Wall](Compendium/Mechanics/CLI/spells/wind-wall-xphb.md)

- [Wish](Compendium/Mechanics/CLI/spells/wish-xphb.md)

- [Witch Bolt](Compendium/Mechanics/CLI/spells/witch-bolt-xphb.md)

- [Word of Radiance](Compendium/Mechanics/CLI/spells/word-of-radiance-xphb.md)

- [Word of Recall](Compendium/Mechanics/CLI/spells/word-of-recall-xphb.md)

- [Wrathful Smite](Compendium/Mechanics/CLI/spells/wrathful-smite-xphb.md)

- [Yolande's Regal Presence](Compendium/Mechanics/CLI/spells/yolandes-regal-presence-xphb.md)

- [Zone of Truth](Compendium/Mechanics/CLI/spells/zone-of-truth-xphb.md)

## A

> [!embed-spell]- Acid Splash
> ![Acid Splash](Compendium/Mechanics/CLI/spells/acid-splash-xphb.md)

> [!embed-spell]- Aid
> ![Aid](Compendium/Mechanics/CLI/spells/aid-xphb.md)

> [!embed-spell]- Alarm
> ![Alarm](Compendium/Mechanics/CLI/spells/alarm-xphb.md)

> [!embed-spell]- Alter Self
> ![Alter Self](Compendium/Mechanics/CLI/spells/alter-self-xphb.md)

> [!embed-spell]- Animal Friendship
> ![Animal Friendship](Compendium/Mechanics/CLI/spells/animal-friendship-xphb.md)

> [!embed-spell]- Animal Messenger
> ![Animal Messenger](Compendium/Mechanics/CLI/spells/animal-messenger-xphb.md)

> [!embed-spell]- Animal Shapes
> ![Animal Shapes](Compendium/Mechanics/CLI/spells/animal-shapes-xphb.md)

> [!embed-spell]- Animate Dead
> ![Animate Dead](Compendium/Mechanics/CLI/spells/animate-dead-xphb.md)

> [!embed-spell]- Animate Objects
> ![Animate Objects](Compendium/Mechanics/CLI/spells/animate-objects-xphb.md)

> [!embed-spell]- Antilife Shell
> ![Antilife Shell](Compendium/Mechanics/CLI/spells/antilife-shell-xphb.md)

> [!embed-spell]- Antimagic Field
> ![Antimagic Field](Compendium/Mechanics/CLI/spells/antimagic-field-xphb.md)

> [!embed-spell]- Antipathy/Sympathy
> ![Antipathy/Sympathy](Compendium/Mechanics/CLI/spells/antipathy-sympathy-xphb.md)

> [!embed-spell]- Arcane Eye
> ![Arcane Eye](Compendium/Mechanics/CLI/spells/arcane-eye-xphb.md)

> [!embed-spell]- Arcane Gate
> ![Arcane Gate](Compendium/Mechanics/CLI/spells/arcane-gate-xphb.md)

> [!embed-spell]- Arcane Lock
> ![Arcane Lock](Compendium/Mechanics/CLI/spells/arcane-lock-xphb.md)

> [!embed-spell]- Arcane Vigor
> ![Arcane Vigor](Compendium/Mechanics/CLI/spells/arcane-vigor-xphb.md)

> [!embed-spell]- Armor of Agathys
> ![Armor of Agathys](Compendium/Mechanics/CLI/spells/armor-of-agathys-xphb.md)

> [!embed-spell]- Arms of Hadar
> ![Arms of Hadar](Compendium/Mechanics/CLI/spells/arms-of-hadar-xphb.md)

> [!embed-spell]- Astral Projection
> ![Astral Projection](Compendium/Mechanics/CLI/spells/astral-projection-xphb.md)

> [!embed-spell]- Augury
> ![Augury](Compendium/Mechanics/CLI/spells/augury-xphb.md)

> [!embed-spell]- Aura of Life
> ![Aura of Life](Compendium/Mechanics/CLI/spells/aura-of-life-xphb.md)

> [!embed-spell]- Aura of Purity
> ![Aura of Purity](Compendium/Mechanics/CLI/spells/aura-of-purity-xphb.md)

> [!embed-spell]- Aura of Vitality
> ![Aura of Vitality](Compendium/Mechanics/CLI/spells/aura-of-vitality-xphb.md)

> [!embed-spell]- Awaken
> ![Awaken](Compendium/Mechanics/CLI/spells/awaken-xphb.md)

## B

> [!embed-spell]- Bane
> ![Bane](Compendium/Mechanics/CLI/spells/bane-xphb.md)

> [!embed-spell]- Banishing Smite
> ![Banishing Smite](Compendium/Mechanics/CLI/spells/banishing-smite-xphb.md)

> [!embed-spell]- Banishment
> ![Banishment](Compendium/Mechanics/CLI/spells/banishment-xphb.md)

> [!embed-spell]- Barkskin
> ![Barkskin](Compendium/Mechanics/CLI/spells/barkskin-xphb.md)

> [!embed-spell]- Beacon of Hope
> ![Beacon of Hope](Compendium/Mechanics/CLI/spells/beacon-of-hope-xphb.md)

> [!embed-spell]- Beast Sense
> ![Beast Sense](Compendium/Mechanics/CLI/spells/beast-sense-xphb.md)

> [!embed-spell]- Befuddlement
> ![Befuddlement](Compendium/Mechanics/CLI/spells/befuddlement-xphb.md)

> [!embed-spell]- Bestow Curse
> ![Bestow Curse](Compendium/Mechanics/CLI/spells/bestow-curse-xphb.md)

> [!embed-spell]- Bigby's Hand
> ![Bigby's Hand](Compendium/Mechanics/CLI/spells/bigbys-hand-xphb.md)

> [!embed-spell]- Blade Barrier
> ![Blade Barrier](Compendium/Mechanics/CLI/spells/blade-barrier-xphb.md)

> [!embed-spell]- Blade Ward
> ![Blade Ward](Compendium/Mechanics/CLI/spells/blade-ward-xphb.md)

> [!embed-spell]- Bless
> ![Bless](Compendium/Mechanics/CLI/spells/bless-xphb.md)

> [!embed-spell]- Blight
> ![Blight](Compendium/Mechanics/CLI/spells/blight-xphb.md)

> [!embed-spell]- Blinding Smite
> ![Blinding Smite](Compendium/Mechanics/CLI/spells/blinding-smite-xphb.md)

> [!embed-spell]- Blindness/Deafness
> ![Blindness/Deafness](Compendium/Mechanics/CLI/spells/blindness-deafness-xphb.md)

> [!embed-spell]- Blink
> ![Blink](Compendium/Mechanics/CLI/spells/blink-xphb.md)

> [!embed-spell]- Blur
> ![Blur](Compendium/Mechanics/CLI/spells/blur-xphb.md)

> [!embed-spell]- Burning Hands
> ![Burning Hands](Compendium/Mechanics/CLI/spells/burning-hands-xphb.md)

## C

> [!embed-spell]- Call Lightning
> ![Call Lightning](Compendium/Mechanics/CLI/spells/call-lightning-xphb.md)

> [!embed-spell]- Calm Emotions
> ![Calm Emotions](Compendium/Mechanics/CLI/spells/calm-emotions-xphb.md)

> [!embed-spell]- Chain Lightning
> ![Chain Lightning](Compendium/Mechanics/CLI/spells/chain-lightning-xphb.md)

> [!embed-spell]- Charm Monster
> ![Charm Monster](Compendium/Mechanics/CLI/spells/charm-monster-xphb.md)

> [!embed-spell]- Charm Person
> ![Charm Person](Compendium/Mechanics/CLI/spells/charm-person-xphb.md)

> [!embed-spell]- Chill Touch
> ![Chill Touch](Compendium/Mechanics/CLI/spells/chill-touch-xphb.md)

> [!embed-spell]- Chromatic Orb
> ![Chromatic Orb](Compendium/Mechanics/CLI/spells/chromatic-orb-xphb.md)

> [!embed-spell]- Circle of Death
> ![Circle of Death](Compendium/Mechanics/CLI/spells/circle-of-death-xphb.md)

> [!embed-spell]- Circle of Power
> ![Circle of Power](Compendium/Mechanics/CLI/spells/circle-of-power-xphb.md)

> [!embed-spell]- Clairvoyance
> ![Clairvoyance](Compendium/Mechanics/CLI/spells/clairvoyance-xphb.md)

> [!embed-spell]- Clone
> ![Clone](Compendium/Mechanics/CLI/spells/clone-xphb.md)

> [!embed-spell]- Cloud of Daggers
> ![Cloud of Daggers](Compendium/Mechanics/CLI/spells/cloud-of-daggers-xphb.md)

> [!embed-spell]- Cloudkill
> ![Cloudkill](Compendium/Mechanics/CLI/spells/cloudkill-xphb.md)

> [!embed-spell]- Color Spray
> ![Color Spray](Compendium/Mechanics/CLI/spells/color-spray-xphb.md)

> [!embed-spell]- Command
> ![Command](Compendium/Mechanics/CLI/spells/command-xphb.md)

> [!embed-spell]- Commune
> ![Commune](Compendium/Mechanics/CLI/spells/commune-xphb.md)

> [!embed-spell]- Commune with Nature
> ![Commune with Nature](Compendium/Mechanics/CLI/spells/commune-with-nature-xphb.md)

> [!embed-spell]- Compelled Duel
> ![Compelled Duel](Compendium/Mechanics/CLI/spells/compelled-duel-xphb.md)

> [!embed-spell]- Comprehend Languages
> ![Comprehend Languages](Compendium/Mechanics/CLI/spells/comprehend-languages-xphb.md)

> [!embed-spell]- Compulsion
> ![Compulsion](Compendium/Mechanics/CLI/spells/compulsion-xphb.md)

> [!embed-spell]- Cone of Cold
> ![Cone of Cold](Compendium/Mechanics/CLI/spells/cone-of-cold-xphb.md)

> [!embed-spell]- Confusion
> ![Confusion](Compendium/Mechanics/CLI/spells/confusion-xphb.md)

> [!embed-spell]- Conjure Animals
> ![Conjure Animals](Compendium/Mechanics/CLI/spells/conjure-animals-xphb.md)

> [!embed-spell]- Conjure Barrage
> ![Conjure Barrage](Compendium/Mechanics/CLI/spells/conjure-barrage-xphb.md)

> [!embed-spell]- Conjure Celestial
> ![Conjure Celestial](Compendium/Mechanics/CLI/spells/conjure-celestial-xphb.md)

> [!embed-spell]- Conjure Elemental
> ![Conjure Elemental](Compendium/Mechanics/CLI/spells/conjure-elemental-xphb.md)

> [!embed-spell]- Conjure Fey
> ![Conjure Fey](Compendium/Mechanics/CLI/spells/conjure-fey-xphb.md)

> [!embed-spell]- Conjure Minor Elementals
> ![Conjure Minor Elementals](Compendium/Mechanics/CLI/spells/conjure-minor-elementals-xphb.md)

> [!embed-spell]- Conjure Volley
> ![Conjure Volley](Compendium/Mechanics/CLI/spells/conjure-volley-xphb.md)

> [!embed-spell]- Conjure Woodland Beings
> ![Conjure Woodland Beings](Compendium/Mechanics/CLI/spells/conjure-woodland-beings-xphb.md)

> [!embed-spell]- Contact Other Plane
> ![Contact Other Plane](Compendium/Mechanics/CLI/spells/contact-other-plane-xphb.md)

> [!embed-spell]- Contagion
> ![Contagion](Compendium/Mechanics/CLI/spells/contagion-xphb.md)

> [!embed-spell]- Contingency
> ![Contingency](Compendium/Mechanics/CLI/spells/contingency-xphb.md)

> [!embed-spell]- Continual Flame
> ![Continual Flame](Compendium/Mechanics/CLI/spells/continual-flame-xphb.md)

> [!embed-spell]- Control Water
> ![Control Water](Compendium/Mechanics/CLI/spells/control-water-xphb.md)

> [!embed-spell]- Control Weather
> ![Control Weather](Compendium/Mechanics/CLI/spells/control-weather-xphb.md)

> [!embed-spell]- Cordon of Arrows
> ![Cordon of Arrows](Compendium/Mechanics/CLI/spells/cordon-of-arrows-xphb.md)

> [!embed-spell]- Counterspell
> ![Counterspell](Compendium/Mechanics/CLI/spells/counterspell-xphb.md)

> [!embed-spell]- Create Food and Water
> ![Create Food and Water](Compendium/Mechanics/CLI/spells/create-food-and-water-xphb.md)

> [!embed-spell]- Create or Destroy Water
> ![Create or Destroy Water](Compendium/Mechanics/CLI/spells/create-or-destroy-water-xphb.md)

> [!embed-spell]- Create Undead
> ![Create Undead](Compendium/Mechanics/CLI/spells/create-undead-xphb.md)

> [!embed-spell]- Creation
> ![Creation](Compendium/Mechanics/CLI/spells/creation-xphb.md)

> [!embed-spell]- Crown of Madness
> ![Crown of Madness](Compendium/Mechanics/CLI/spells/crown-of-madness-xphb.md)

> [!embed-spell]- Crusader's Mantle
> ![Crusader's Mantle](Compendium/Mechanics/CLI/spells/crusaders-mantle-xphb.md)

> [!embed-spell]- Cure Wounds
> ![Cure Wounds](Compendium/Mechanics/CLI/spells/cure-wounds-xphb.md)

## D

> [!embed-spell]- Dancing Lights
> ![Dancing Lights](Compendium/Mechanics/CLI/spells/dancing-lights-xphb.md)

> [!embed-spell]- Darkness
> ![Darkness](Compendium/Mechanics/CLI/spells/darkness-xphb.md)

> [!embed-spell]- Darkvision
> ![Darkvision](Compendium/Mechanics/CLI/spells/darkvision-xphb.md)

> [!embed-spell]- Daylight
> ![Daylight](Compendium/Mechanics/CLI/spells/daylight-xphb.md)

> [!embed-spell]- Death Ward
> ![Death Ward](Compendium/Mechanics/CLI/spells/death-ward-xphb.md)

> [!embed-spell]- Delayed Blast Fireball
> ![Delayed Blast Fireball](Compendium/Mechanics/CLI/spells/delayed-blast-fireball-xphb.md)

> [!embed-spell]- Demiplane
> ![Demiplane](Compendium/Mechanics/CLI/spells/demiplane-xphb.md)

> [!embed-spell]- Destructive Wave
> ![Destructive Wave](Compendium/Mechanics/CLI/spells/destructive-wave-xphb.md)

> [!embed-spell]- Detect Evil and Good
> ![Detect Evil and Good](Compendium/Mechanics/CLI/spells/detect-evil-and-good-xphb.md)

> [!embed-spell]- Detect Magic
> ![Detect Magic](Compendium/Mechanics/CLI/spells/detect-magic-xphb.md)

> [!embed-spell]- Detect Poison and Disease
> ![Detect Poison and Disease](Compendium/Mechanics/CLI/spells/detect-poison-and-disease-xphb.md)

> [!embed-spell]- Detect Thoughts
> ![Detect Thoughts](Compendium/Mechanics/CLI/spells/detect-thoughts-xphb.md)

> [!embed-spell]- Dimension Door
> ![Dimension Door](Compendium/Mechanics/CLI/spells/dimension-door-xphb.md)

> [!embed-spell]- Disguise Self
> ![Disguise Self](Compendium/Mechanics/CLI/spells/disguise-self-xphb.md)

> [!embed-spell]- Disintegrate
> ![Disintegrate](Compendium/Mechanics/CLI/spells/disintegrate-xphb.md)

> [!embed-spell]- Dispel Evil and Good
> ![Dispel Evil and Good](Compendium/Mechanics/CLI/spells/dispel-evil-and-good-xphb.md)

> [!embed-spell]- Dispel Magic
> ![Dispel Magic](Compendium/Mechanics/CLI/spells/dispel-magic-xphb.md)

> [!embed-spell]- Dissonant Whispers
> ![Dissonant Whispers](Compendium/Mechanics/CLI/spells/dissonant-whispers-xphb.md)

> [!embed-spell]- Divination
> ![Divination](Compendium/Mechanics/CLI/spells/divination-xphb.md)

> [!embed-spell]- Divine Favor
> ![Divine Favor](Compendium/Mechanics/CLI/spells/divine-favor-xphb.md)

> [!embed-spell]- Divine Smite
> ![Divine Smite](Compendium/Mechanics/CLI/spells/divine-smite-xphb.md)

> [!embed-spell]- Divine Word
> ![Divine Word](Compendium/Mechanics/CLI/spells/divine-word-xphb.md)

> [!embed-spell]- Dominate Beast
> ![Dominate Beast](Compendium/Mechanics/CLI/spells/dominate-beast-xphb.md)

> [!embed-spell]- Dominate Monster
> ![Dominate Monster](Compendium/Mechanics/CLI/spells/dominate-monster-xphb.md)

> [!embed-spell]- Dominate Person
> ![Dominate Person](Compendium/Mechanics/CLI/spells/dominate-person-xphb.md)

> [!embed-spell]- Dragon's Breath
> ![Dragon's Breath](Compendium/Mechanics/CLI/spells/dragons-breath-xphb.md)

> [!embed-spell]- Drawmij's Instant Summons
> ![Drawmij's Instant Summons](Compendium/Mechanics/CLI/spells/drawmijs-instant-summons-xphb.md)

> [!embed-spell]- Dream
> ![Dream](Compendium/Mechanics/CLI/spells/dream-xphb.md)

> [!embed-spell]- Druidcraft
> ![Druidcraft](Compendium/Mechanics/CLI/spells/druidcraft-xphb.md)

## E

> [!embed-spell]- Earthquake
> ![Earthquake](Compendium/Mechanics/CLI/spells/earthquake-xphb.md)

> [!embed-spell]- Eldritch Blast
> ![Eldritch Blast](Compendium/Mechanics/CLI/spells/eldritch-blast-xphb.md)

> [!embed-spell]- Elemental Weapon
> ![Elemental Weapon](Compendium/Mechanics/CLI/spells/elemental-weapon-xphb.md)

> [!embed-spell]- Elementalism
> ![Elementalism](Compendium/Mechanics/CLI/spells/elementalism-xphb.md)

> [!embed-spell]- Enhance Ability
> ![Enhance Ability](Compendium/Mechanics/CLI/spells/enhance-ability-xphb.md)

> [!embed-spell]- Enlarge/Reduce
> ![Enlarge/Reduce](Compendium/Mechanics/CLI/spells/enlarge-reduce-xphb.md)

> [!embed-spell]- Ensnaring Strike
> ![Ensnaring Strike](Compendium/Mechanics/CLI/spells/ensnaring-strike-xphb.md)

> [!embed-spell]- Entangle
> ![Entangle](Compendium/Mechanics/CLI/spells/entangle-xphb.md)

> [!embed-spell]- Enthrall
> ![Enthrall](Compendium/Mechanics/CLI/spells/enthrall-xphb.md)

> [!embed-spell]- Etherealness
> ![Etherealness](Compendium/Mechanics/CLI/spells/etherealness-xphb.md)

> [!embed-spell]- Evard's Black Tentacles
> ![Evard's Black Tentacles](Compendium/Mechanics/CLI/spells/evards-black-tentacles-xphb.md)

> [!embed-spell]- Expeditious Retreat
> ![Expeditious Retreat](Compendium/Mechanics/CLI/spells/expeditious-retreat-xphb.md)

> [!embed-spell]- Eyebite
> ![Eyebite](Compendium/Mechanics/CLI/spells/eyebite-xphb.md)

## F

> [!embed-spell]- Fabricate
> ![Fabricate](Compendium/Mechanics/CLI/spells/fabricate-xphb.md)

> [!embed-spell]- Faerie Fire
> ![Faerie Fire](Compendium/Mechanics/CLI/spells/faerie-fire-xphb.md)

> [!embed-spell]- False Life
> ![False Life](Compendium/Mechanics/CLI/spells/false-life-xphb.md)

> [!embed-spell]- Fear
> ![Fear](Compendium/Mechanics/CLI/spells/fear-xphb.md)

> [!embed-spell]- Feather Fall
> ![Feather Fall](Compendium/Mechanics/CLI/spells/feather-fall-xphb.md)

> [!embed-spell]- Feign Death
> ![Feign Death](Compendium/Mechanics/CLI/spells/feign-death-xphb.md)

> [!embed-spell]- Find Familiar
> ![Find Familiar](Compendium/Mechanics/CLI/spells/find-familiar-xphb.md)

> [!embed-spell]- Find Steed
> ![Find Steed](Compendium/Mechanics/CLI/spells/find-steed-xphb.md)

> [!embed-spell]- Find the Path
> ![Find the Path](Compendium/Mechanics/CLI/spells/find-the-path-xphb.md)

> [!embed-spell]- Find Traps
> ![Find Traps](Compendium/Mechanics/CLI/spells/find-traps-xphb.md)

> [!embed-spell]- Finger of Death
> ![Finger of Death](Compendium/Mechanics/CLI/spells/finger-of-death-xphb.md)

> [!embed-spell]- Fire Bolt
> ![Fire Bolt](Compendium/Mechanics/CLI/spells/fire-bolt-xphb.md)

> [!embed-spell]- Fire Shield
> ![Fire Shield](Compendium/Mechanics/CLI/spells/fire-shield-xphb.md)

> [!embed-spell]- Fire Storm
> ![Fire Storm](Compendium/Mechanics/CLI/spells/fire-storm-xphb.md)

> [!embed-spell]- Fireball
> ![Fireball](Compendium/Mechanics/CLI/spells/fireball-xphb.md)

> [!embed-spell]- Flame Blade
> ![Flame Blade](Compendium/Mechanics/CLI/spells/flame-blade-xphb.md)

> [!embed-spell]- Flame Strike
> ![Flame Strike](Compendium/Mechanics/CLI/spells/flame-strike-xphb.md)

> [!embed-spell]- Flaming Sphere
> ![Flaming Sphere](Compendium/Mechanics/CLI/spells/flaming-sphere-xphb.md)

> [!embed-spell]- Flesh to Stone
> ![Flesh to Stone](Compendium/Mechanics/CLI/spells/flesh-to-stone-xphb.md)

> [!embed-spell]- Fly
> ![Fly](Compendium/Mechanics/CLI/spells/fly-xphb.md)

> [!embed-spell]- Fog Cloud
> ![Fog Cloud](Compendium/Mechanics/CLI/spells/fog-cloud-xphb.md)

> [!embed-spell]- Forbiddance
> ![Forbiddance](Compendium/Mechanics/CLI/spells/forbiddance-xphb.md)

> [!embed-spell]- Forcecage
> ![Forcecage](Compendium/Mechanics/CLI/spells/forcecage-xphb.md)

> [!embed-spell]- Foresight
> ![Foresight](Compendium/Mechanics/CLI/spells/foresight-xphb.md)

> [!embed-spell]- Fount of Moonlight
> ![Fount of Moonlight](Compendium/Mechanics/CLI/spells/fount-of-moonlight-xphb.md)

> [!embed-spell]- Freedom of Movement
> ![Freedom of Movement](Compendium/Mechanics/CLI/spells/freedom-of-movement-xphb.md)

> [!embed-spell]- Friends
> ![Friends](Compendium/Mechanics/CLI/spells/friends-xphb.md)

## G

> [!embed-spell]- Gaseous Form
> ![Gaseous Form](Compendium/Mechanics/CLI/spells/gaseous-form-xphb.md)

> [!embed-spell]- Gate
> ![Gate](Compendium/Mechanics/CLI/spells/gate-xphb.md)

> [!embed-spell]- Geas
> ![Geas](Compendium/Mechanics/CLI/spells/geas-xphb.md)

> [!embed-spell]- Gentle Repose
> ![Gentle Repose](Compendium/Mechanics/CLI/spells/gentle-repose-xphb.md)

> [!embed-spell]- Giant Insect
> ![Giant Insect](Compendium/Mechanics/CLI/spells/giant-insect-xphb.md)

> [!embed-spell]- Glibness
> ![Glibness](Compendium/Mechanics/CLI/spells/glibness-xphb.md)

> [!embed-spell]- Globe of Invulnerability
> ![Globe of Invulnerability](Compendium/Mechanics/CLI/spells/globe-of-invulnerability-xphb.md)

> [!embed-spell]- Glyph of Warding
> ![Glyph of Warding](Compendium/Mechanics/CLI/spells/glyph-of-warding-xphb.md)

> [!embed-spell]- Goodberry
> ![Goodberry](Compendium/Mechanics/CLI/spells/goodberry-xphb.md)

> [!embed-spell]- Grasping Vine
> ![Grasping Vine](Compendium/Mechanics/CLI/spells/grasping-vine-xphb.md)

> [!embed-spell]- Grease
> ![Grease](Compendium/Mechanics/CLI/spells/grease-xphb.md)

> [!embed-spell]- Greater Invisibility
> ![Greater Invisibility](Compendium/Mechanics/CLI/spells/greater-invisibility-xphb.md)

> [!embed-spell]- Greater Restoration
> ![Greater Restoration](Compendium/Mechanics/CLI/spells/greater-restoration-xphb.md)

> [!embed-spell]- Guardian of Faith
> ![Guardian of Faith](Compendium/Mechanics/CLI/spells/guardian-of-faith-xphb.md)

> [!embed-spell]- Guards and Wards
> ![Guards and Wards](Compendium/Mechanics/CLI/spells/guards-and-wards-xphb.md)

> [!embed-spell]- Guidance
> ![Guidance](Compendium/Mechanics/CLI/spells/guidance-xphb.md)

> [!embed-spell]- Guiding Bolt
> ![Guiding Bolt](Compendium/Mechanics/CLI/spells/guiding-bolt-xphb.md)

> [!embed-spell]- Gust of Wind
> ![Gust of Wind](Compendium/Mechanics/CLI/spells/gust-of-wind-xphb.md)

## H

> [!embed-spell]- Hail of Thorns
> ![Hail of Thorns](Compendium/Mechanics/CLI/spells/hail-of-thorns-xphb.md)

> [!embed-spell]- Hallow
> ![Hallow](Compendium/Mechanics/CLI/spells/hallow-xphb.md)

> [!embed-spell]- Hallucinatory Terrain
> ![Hallucinatory Terrain](Compendium/Mechanics/CLI/spells/hallucinatory-terrain-xphb.md)

> [!embed-spell]- Harm
> ![Harm](Compendium/Mechanics/CLI/spells/harm-xphb.md)

> [!embed-spell]- Haste
> ![Haste](Compendium/Mechanics/CLI/spells/haste-xphb.md)

> [!embed-spell]- Heal
> ![Heal](Compendium/Mechanics/CLI/spells/heal-xphb.md)

> [!embed-spell]- Healing Word
> ![Healing Word](Compendium/Mechanics/CLI/spells/healing-word-xphb.md)

> [!embed-spell]- Heat Metal
> ![Heat Metal](Compendium/Mechanics/CLI/spells/heat-metal-xphb.md)

> [!embed-spell]- Hellish Rebuke
> ![Hellish Rebuke](Compendium/Mechanics/CLI/spells/hellish-rebuke-xphb.md)

> [!embed-spell]- Heroes' Feast
> ![Heroes' Feast](Compendium/Mechanics/CLI/spells/heroes-feast-xphb.md)

> [!embed-spell]- Heroism
> ![Heroism](Compendium/Mechanics/CLI/spells/heroism-xphb.md)

> [!embed-spell]- Hex
> ![Hex](Compendium/Mechanics/CLI/spells/hex-xphb.md)

> [!embed-spell]- Hold Monster
> ![Hold Monster](Compendium/Mechanics/CLI/spells/hold-monster-xphb.md)

> [!embed-spell]- Hold Person
> ![Hold Person](Compendium/Mechanics/CLI/spells/hold-person-xphb.md)

> [!embed-spell]- Holy Aura
> ![Holy Aura](Compendium/Mechanics/CLI/spells/holy-aura-xphb.md)

> [!embed-spell]- Hunger of Hadar
> ![Hunger of Hadar](Compendium/Mechanics/CLI/spells/hunger-of-hadar-xphb.md)

> [!embed-spell]- Hunter's Mark
> ![Hunter's Mark](Compendium/Mechanics/CLI/spells/hunters-mark-xphb.md)

> [!embed-spell]- Hypnotic Pattern
> ![Hypnotic Pattern](Compendium/Mechanics/CLI/spells/hypnotic-pattern-xphb.md)

## I

> [!embed-spell]- Ice Knife
> ![Ice Knife](Compendium/Mechanics/CLI/spells/ice-knife-xphb.md)

> [!embed-spell]- Ice Storm
> ![Ice Storm](Compendium/Mechanics/CLI/spells/ice-storm-xphb.md)

> [!embed-spell]- Identify
> ![Identify](Compendium/Mechanics/CLI/spells/identify-xphb.md)

> [!embed-spell]- Illusory Script
> ![Illusory Script](Compendium/Mechanics/CLI/spells/illusory-script-xphb.md)

> [!embed-spell]- Imprisonment
> ![Imprisonment](Compendium/Mechanics/CLI/spells/imprisonment-xphb.md)

> [!embed-spell]- Incendiary Cloud
> ![Incendiary Cloud](Compendium/Mechanics/CLI/spells/incendiary-cloud-xphb.md)

> [!embed-spell]- Inflict Wounds
> ![Inflict Wounds](Compendium/Mechanics/CLI/spells/inflict-wounds-xphb.md)

> [!embed-spell]- Insect Plague
> ![Insect Plague](Compendium/Mechanics/CLI/spells/insect-plague-xphb.md)

> [!embed-spell]- Invisibility
> ![Invisibility](Compendium/Mechanics/CLI/spells/invisibility-xphb.md)

## J

> [!embed-spell]- Jallarzi's Storm of Radiance
> ![Jallarzi's Storm of Radiance](Compendium/Mechanics/CLI/spells/jallarzis-storm-of-radiance-xphb.md)

> [!embed-spell]- Jump
> ![Jump](Compendium/Mechanics/CLI/spells/jump-xphb.md)

## K

> [!embed-spell]- Knock
> ![Knock](Compendium/Mechanics/CLI/spells/knock-xphb.md)

## L

> [!embed-spell]- Legend Lore
> ![Legend Lore](Compendium/Mechanics/CLI/spells/legend-lore-xphb.md)

> [!embed-spell]- Leomund's Secret Chest
> ![Leomund's Secret Chest](Compendium/Mechanics/CLI/spells/leomunds-secret-chest-xphb.md)

> [!embed-spell]- Leomund's Tiny Hut
> ![Leomund's Tiny Hut](Compendium/Mechanics/CLI/spells/leomunds-tiny-hut-xphb.md)

> [!embed-spell]- Lesser Restoration
> ![Lesser Restoration](Compendium/Mechanics/CLI/spells/lesser-restoration-xphb.md)

> [!embed-spell]- Levitate
> ![Levitate](Compendium/Mechanics/CLI/spells/levitate-xphb.md)

> [!embed-spell]- Light
> ![Light](Compendium/Mechanics/CLI/spells/light-xphb.md)

> [!embed-spell]- Lightning Arrow
> ![Lightning Arrow](Compendium/Mechanics/CLI/spells/lightning-arrow-xphb.md)

> [!embed-spell]- Lightning Bolt
> ![Lightning Bolt](Compendium/Mechanics/CLI/spells/lightning-bolt-xphb.md)

> [!embed-spell]- Locate Animals or Plants
> ![Locate Animals or Plants](Compendium/Mechanics/CLI/spells/locate-animals-or-plants-xphb.md)

> [!embed-spell]- Locate Creature
> ![Locate Creature](Compendium/Mechanics/CLI/spells/locate-creature-xphb.md)

> [!embed-spell]- Locate Object
> ![Locate Object](Compendium/Mechanics/CLI/spells/locate-object-xphb.md)

> [!embed-spell]- Longstrider
> ![Longstrider](Compendium/Mechanics/CLI/spells/longstrider-xphb.md)

## M

> [!embed-spell]- Mage Armor
> ![Mage Armor](Compendium/Mechanics/CLI/spells/mage-armor-xphb.md)

> [!embed-spell]- Mage Hand
> ![Mage Hand](Compendium/Mechanics/CLI/spells/mage-hand-xphb.md)

> [!embed-spell]- Magic Circle
> ![Magic Circle](Compendium/Mechanics/CLI/spells/magic-circle-xphb.md)

> [!embed-spell]- Magic Jar
> ![Magic Jar](Compendium/Mechanics/CLI/spells/magic-jar-xphb.md)

> [!embed-spell]- Magic Missile
> ![Magic Missile](Compendium/Mechanics/CLI/spells/magic-missile-xphb.md)

> [!embed-spell]- Magic Mouth
> ![Magic Mouth](Compendium/Mechanics/CLI/spells/magic-mouth-xphb.md)

> [!embed-spell]- Magic Weapon
> ![Magic Weapon](Compendium/Mechanics/CLI/spells/magic-weapon-xphb.md)

> [!embed-spell]- Major Image
> ![Major Image](Compendium/Mechanics/CLI/spells/major-image-xphb.md)

> [!embed-spell]- Mass Cure Wounds
> ![Mass Cure Wounds](Compendium/Mechanics/CLI/spells/mass-cure-wounds-xphb.md)

> [!embed-spell]- Mass Heal
> ![Mass Heal](Compendium/Mechanics/CLI/spells/mass-heal-xphb.md)

> [!embed-spell]- Mass Healing Word
> ![Mass Healing Word](Compendium/Mechanics/CLI/spells/mass-healing-word-xphb.md)

> [!embed-spell]- Mass Suggestion
> ![Mass Suggestion](Compendium/Mechanics/CLI/spells/mass-suggestion-xphb.md)

> [!embed-spell]- Maze
> ![Maze](Compendium/Mechanics/CLI/spells/maze-xphb.md)

> [!embed-spell]- Meld into Stone
> ![Meld into Stone](Compendium/Mechanics/CLI/spells/meld-into-stone-xphb.md)

> [!embed-spell]- Melf's Acid Arrow
> ![Melf's Acid Arrow](Compendium/Mechanics/CLI/spells/melfs-acid-arrow-xphb.md)

> [!embed-spell]- Mending
> ![Mending](Compendium/Mechanics/CLI/spells/mending-xphb.md)

> [!embed-spell]- Message
> ![Message](Compendium/Mechanics/CLI/spells/message-xphb.md)

> [!embed-spell]- Meteor Swarm
> ![Meteor Swarm](Compendium/Mechanics/CLI/spells/meteor-swarm-xphb.md)

> [!embed-spell]- Mind Blank
> ![Mind Blank](Compendium/Mechanics/CLI/spells/mind-blank-xphb.md)

> [!embed-spell]- Mind Sliver
> ![Mind Sliver](Compendium/Mechanics/CLI/spells/mind-sliver-xphb.md)

> [!embed-spell]- Mind Spike
> ![Mind Spike](Compendium/Mechanics/CLI/spells/mind-spike-xphb.md)

> [!embed-spell]- Minor Illusion
> ![Minor Illusion](Compendium/Mechanics/CLI/spells/minor-illusion-xphb.md)

> [!embed-spell]- Mirage Arcane
> ![Mirage Arcane](Compendium/Mechanics/CLI/spells/mirage-arcane-xphb.md)

> [!embed-spell]- Mirror Image
> ![Mirror Image](Compendium/Mechanics/CLI/spells/mirror-image-xphb.md)

> [!embed-spell]- Mislead
> ![Mislead](Compendium/Mechanics/CLI/spells/mislead-xphb.md)

> [!embed-spell]- Misty Step
> ![Misty Step](Compendium/Mechanics/CLI/spells/misty-step-xphb.md)

> [!embed-spell]- Modify Memory
> ![Modify Memory](Compendium/Mechanics/CLI/spells/modify-memory-xphb.md)

> [!embed-spell]- Moonbeam
> ![Moonbeam](Compendium/Mechanics/CLI/spells/moonbeam-xphb.md)

> [!embed-spell]- Mordenkainen's Faithful Hound
> ![Mordenkainen's Faithful Hound](Compendium/Mechanics/CLI/spells/mordenkainens-faithful-hound-xphb.md)

> [!embed-spell]- Mordenkainen's Magnificent Mansion
> ![Mordenkainen's Magnificent Mansion](Compendium/Mechanics/CLI/spells/mordenkainens-magnificent-mansion-xphb.md)

> [!embed-spell]- Mordenkainen's Private Sanctum
> ![Mordenkainen's Private Sanctum](Compendium/Mechanics/CLI/spells/mordenkainens-private-sanctum-xphb.md)

> [!embed-spell]- Mordenkainen's Sword
> ![Mordenkainen's Sword](Compendium/Mechanics/CLI/spells/mordenkainens-sword-xphb.md)

> [!embed-spell]- Move Earth
> ![Move Earth](Compendium/Mechanics/CLI/spells/move-earth-xphb.md)

## N

> [!embed-spell]- Nondetection
> ![Nondetection](Compendium/Mechanics/CLI/spells/nondetection-xphb.md)

> [!embed-spell]- Nystul's Magic Aura
> ![Nystul's Magic Aura](Compendium/Mechanics/CLI/spells/nystuls-magic-aura-xphb.md)

## O

> [!embed-spell]- Otiluke's Freezing Sphere
> ![Otiluke's Freezing Sphere](Compendium/Mechanics/CLI/spells/otilukes-freezing-sphere-xphb.md)

> [!embed-spell]- Otiluke's Resilient Sphere
> ![Otiluke's Resilient Sphere](Compendium/Mechanics/CLI/spells/otilukes-resilient-sphere-xphb.md)

> [!embed-spell]- Otto's Irresistible Dance
> ![Otto's Irresistible Dance](Compendium/Mechanics/CLI/spells/ottos-irresistible-dance-xphb.md)

## P

> [!embed-spell]- Pass without Trace
> ![Pass without Trace](Compendium/Mechanics/CLI/spells/pass-without-trace-xphb.md)

> [!embed-spell]- Passwall
> ![Passwall](Compendium/Mechanics/CLI/spells/passwall-xphb.md)

> [!embed-spell]- Phantasmal Force
> ![Phantasmal Force](Compendium/Mechanics/CLI/spells/phantasmal-force-xphb.md)

> [!embed-spell]- Phantasmal Killer
> ![Phantasmal Killer](Compendium/Mechanics/CLI/spells/phantasmal-killer-xphb.md)

> [!embed-spell]- Phantom Steed
> ![Phantom Steed](Compendium/Mechanics/CLI/spells/phantom-steed-xphb.md)

> [!embed-spell]- Planar Ally
> ![Planar Ally](Compendium/Mechanics/CLI/spells/planar-ally-xphb.md)

> [!embed-spell]- Planar Binding
> ![Planar Binding](Compendium/Mechanics/CLI/spells/planar-binding-xphb.md)

> [!embed-spell]- Plane Shift
> ![Plane Shift](Compendium/Mechanics/CLI/spells/plane-shift-xphb.md)

> [!embed-spell]- Plant Growth
> ![Plant Growth](Compendium/Mechanics/CLI/spells/plant-growth-xphb.md)

> [!embed-spell]- Poison Spray
> ![Poison Spray](Compendium/Mechanics/CLI/spells/poison-spray-xphb.md)

> [!embed-spell]- Polymorph
> ![Polymorph](Compendium/Mechanics/CLI/spells/polymorph-xphb.md)

> [!embed-spell]- Power Word Fortify
> ![Power Word Fortify](Compendium/Mechanics/CLI/spells/power-word-fortify-xphb.md)

> [!embed-spell]- Power Word Heal
> ![Power Word Heal](Compendium/Mechanics/CLI/spells/power-word-heal-xphb.md)

> [!embed-spell]- Power Word Kill
> ![Power Word Kill](Compendium/Mechanics/CLI/spells/power-word-kill-xphb.md)

> [!embed-spell]- Power Word Stun
> ![Power Word Stun](Compendium/Mechanics/CLI/spells/power-word-stun-xphb.md)

> [!embed-spell]- Prayer of Healing
> ![Prayer of Healing](Compendium/Mechanics/CLI/spells/prayer-of-healing-xphb.md)

> [!embed-spell]- Prestidigitation
> ![Prestidigitation](Compendium/Mechanics/CLI/spells/prestidigitation-xphb.md)

> [!embed-spell]- Prismatic Spray
> ![Prismatic Spray](Compendium/Mechanics/CLI/spells/prismatic-spray-xphb.md)

> [!embed-spell]- Prismatic Wall
> ![Prismatic Wall](Compendium/Mechanics/CLI/spells/prismatic-wall-xphb.md)

> [!embed-spell]- Produce Flame
> ![Produce Flame](Compendium/Mechanics/CLI/spells/produce-flame-xphb.md)

> [!embed-spell]- Programmed Illusion
> ![Programmed Illusion](Compendium/Mechanics/CLI/spells/programmed-illusion-xphb.md)

> [!embed-spell]- Project Image
> ![Project Image](Compendium/Mechanics/CLI/spells/project-image-xphb.md)

> [!embed-spell]- Protection from Energy
> ![Protection from Energy](Compendium/Mechanics/CLI/spells/protection-from-energy-xphb.md)

> [!embed-spell]- Protection from Evil and Good
> ![Protection from Evil and Good](Compendium/Mechanics/CLI/spells/protection-from-evil-and-good-xphb.md)

> [!embed-spell]- Protection from Poison
> ![Protection from Poison](Compendium/Mechanics/CLI/spells/protection-from-poison-xphb.md)

> [!embed-spell]- Purify Food and Drink
> ![Purify Food and Drink](Compendium/Mechanics/CLI/spells/purify-food-and-drink-xphb.md)

## R

> [!embed-spell]- Raise Dead
> ![Raise Dead](Compendium/Mechanics/CLI/spells/raise-dead-xphb.md)

> [!embed-spell]- Rary's Telepathic Bond
> ![Rary's Telepathic Bond](Compendium/Mechanics/CLI/spells/rarys-telepathic-bond-xphb.md)

> [!embed-spell]- Ray of Enfeeblement
> ![Ray of Enfeeblement](Compendium/Mechanics/CLI/spells/ray-of-enfeeblement-xphb.md)

> [!embed-spell]- Ray of Frost
> ![Ray of Frost](Compendium/Mechanics/CLI/spells/ray-of-frost-xphb.md)

> [!embed-spell]- Ray of Sickness
> ![Ray of Sickness](Compendium/Mechanics/CLI/spells/ray-of-sickness-xphb.md)

> [!embed-spell]- Regenerate
> ![Regenerate](Compendium/Mechanics/CLI/spells/regenerate-xphb.md)

> [!embed-spell]- Reincarnate
> ![Reincarnate](Compendium/Mechanics/CLI/spells/reincarnate-xphb.md)

> [!embed-spell]- Remove Curse
> ![Remove Curse](Compendium/Mechanics/CLI/spells/remove-curse-xphb.md)

> [!embed-spell]- Resistance
> ![Resistance](Compendium/Mechanics/CLI/spells/resistance-xphb.md)

> [!embed-spell]- Resurrection
> ![Resurrection](Compendium/Mechanics/CLI/spells/resurrection-xphb.md)

> [!embed-spell]- Reverse Gravity
> ![Reverse Gravity](Compendium/Mechanics/CLI/spells/reverse-gravity-xphb.md)

> [!embed-spell]- Revivify
> ![Revivify](Compendium/Mechanics/CLI/spells/revivify-xphb.md)

> [!embed-spell]- Rope Trick
> ![Rope Trick](Compendium/Mechanics/CLI/spells/rope-trick-xphb.md)

## S

> [!embed-spell]- Sacred Flame
> ![Sacred Flame](Compendium/Mechanics/CLI/spells/sacred-flame-xphb.md)

> [!embed-spell]- Sanctuary
> ![Sanctuary](Compendium/Mechanics/CLI/spells/sanctuary-xphb.md)

> [!embed-spell]- Scorching Ray
> ![Scorching Ray](Compendium/Mechanics/CLI/spells/scorching-ray-xphb.md)

> [!embed-spell]- Scrying
> ![Scrying](Compendium/Mechanics/CLI/spells/scrying-xphb.md)

> [!embed-spell]- Searing Smite
> ![Searing Smite](Compendium/Mechanics/CLI/spells/searing-smite-xphb.md)

> [!embed-spell]- See Invisibility
> ![See Invisibility](Compendium/Mechanics/CLI/spells/see-invisibility-xphb.md)

> [!embed-spell]- Seeming
> ![Seeming](Compendium/Mechanics/CLI/spells/seeming-xphb.md)

> [!embed-spell]- Sending
> ![Sending](Compendium/Mechanics/CLI/spells/sending-xphb.md)

> [!embed-spell]- Sequester
> ![Sequester](Compendium/Mechanics/CLI/spells/sequester-xphb.md)

> [!embed-spell]- Shapechange
> ![Shapechange](Compendium/Mechanics/CLI/spells/shapechange-xphb.md)

> [!embed-spell]- Shatter
> ![Shatter](Compendium/Mechanics/CLI/spells/shatter-xphb.md)

> [!embed-spell]- Shield
> ![Shield](Compendium/Mechanics/CLI/spells/shield-xphb.md)

> [!embed-spell]- Shield of Faith
> ![Shield of Faith](Compendium/Mechanics/CLI/spells/shield-of-faith-xphb.md)

> [!embed-spell]- Shillelagh
> ![Shillelagh](Compendium/Mechanics/CLI/spells/shillelagh-xphb.md)

> [!embed-spell]- Shining Smite
> ![Shining Smite](Compendium/Mechanics/CLI/spells/shining-smite-xphb.md)

> [!embed-spell]- Shocking Grasp
> ![Shocking Grasp](Compendium/Mechanics/CLI/spells/shocking-grasp-xphb.md)

> [!embed-spell]- Silence
> ![Silence](Compendium/Mechanics/CLI/spells/silence-xphb.md)

> [!embed-spell]- Silent Image
> ![Silent Image](Compendium/Mechanics/CLI/spells/silent-image-xphb.md)

> [!embed-spell]- Simulacrum
> ![Simulacrum](Compendium/Mechanics/CLI/spells/simulacrum-xphb.md)

> [!embed-spell]- Sleep
> ![Sleep](Compendium/Mechanics/CLI/spells/sleep-xphb.md)

> [!embed-spell]- Sleet Storm
> ![Sleet Storm](Compendium/Mechanics/CLI/spells/sleet-storm-xphb.md)

> [!embed-spell]- Slow
> ![Slow](Compendium/Mechanics/CLI/spells/slow-xphb.md)

> [!embed-spell]- Sorcerous Burst
> ![Sorcerous Burst](Compendium/Mechanics/CLI/spells/sorcerous-burst-xphb.md)

> [!embed-spell]- Spare the Dying
> ![Spare the Dying](Compendium/Mechanics/CLI/spells/spare-the-dying-xphb.md)

> [!embed-spell]- Speak with Animals
> ![Speak with Animals](Compendium/Mechanics/CLI/spells/speak-with-animals-xphb.md)

> [!embed-spell]- Speak with Dead
> ![Speak with Dead](Compendium/Mechanics/CLI/spells/speak-with-dead-xphb.md)

> [!embed-spell]- Speak with Plants
> ![Speak with Plants](Compendium/Mechanics/CLI/spells/speak-with-plants-xphb.md)

> [!embed-spell]- Spider Climb
> ![Spider Climb](Compendium/Mechanics/CLI/spells/spider-climb-xphb.md)

> [!embed-spell]- Spike Growth
> ![Spike Growth](Compendium/Mechanics/CLI/spells/spike-growth-xphb.md)

> [!embed-spell]- Spirit Guardians
> ![Spirit Guardians](Compendium/Mechanics/CLI/spells/spirit-guardians-xphb.md)

> [!embed-spell]- Spiritual Weapon
> ![Spiritual Weapon](Compendium/Mechanics/CLI/spells/spiritual-weapon-xphb.md)

> [!embed-spell]- Staggering Smite
> ![Staggering Smite](Compendium/Mechanics/CLI/spells/staggering-smite-xphb.md)

> [!embed-spell]- Starry Wisp
> ![Starry Wisp](Compendium/Mechanics/CLI/spells/starry-wisp-xphb.md)

> [!embed-spell]- Steel Wind Strike
> ![Steel Wind Strike](Compendium/Mechanics/CLI/spells/steel-wind-strike-xphb.md)

> [!embed-spell]- Stinking Cloud
> ![Stinking Cloud](Compendium/Mechanics/CLI/spells/stinking-cloud-xphb.md)

> [!embed-spell]- Stone Shape
> ![Stone Shape](Compendium/Mechanics/CLI/spells/stone-shape-xphb.md)

> [!embed-spell]- Stoneskin
> ![Stoneskin](Compendium/Mechanics/CLI/spells/stoneskin-xphb.md)

> [!embed-spell]- Storm of Vengeance
> ![Storm of Vengeance](Compendium/Mechanics/CLI/spells/storm-of-vengeance-xphb.md)

> [!embed-spell]- Suggestion
> ![Suggestion](Compendium/Mechanics/CLI/spells/suggestion-xphb.md)

> [!embed-spell]- Summon Aberration
> ![Summon Aberration](Compendium/Mechanics/CLI/spells/summon-aberration-xphb.md)

> [!embed-spell]- Summon Beast
> ![Summon Beast](Compendium/Mechanics/CLI/spells/summon-beast-xphb.md)

> [!embed-spell]- Summon Celestial
> ![Summon Celestial](Compendium/Mechanics/CLI/spells/summon-celestial-xphb.md)

> [!embed-spell]- Summon Construct
> ![Summon Construct](Compendium/Mechanics/CLI/spells/summon-construct-xphb.md)

> [!embed-spell]- Summon Dragon
> ![Summon Dragon](Compendium/Mechanics/CLI/spells/summon-dragon-xphb.md)

> [!embed-spell]- Summon Elemental
> ![Summon Elemental](Compendium/Mechanics/CLI/spells/summon-elemental-xphb.md)

> [!embed-spell]- Summon Fey
> ![Summon Fey](Compendium/Mechanics/CLI/spells/summon-fey-xphb.md)

> [!embed-spell]- Summon Fiend
> ![Summon Fiend](Compendium/Mechanics/CLI/spells/summon-fiend-xphb.md)

> [!embed-spell]- Summon Undead
> ![Summon Undead](Compendium/Mechanics/CLI/spells/summon-undead-xphb.md)

> [!embed-spell]- Sunbeam
> ![Sunbeam](Compendium/Mechanics/CLI/spells/sunbeam-xphb.md)

> [!embed-spell]- Sunburst
> ![Sunburst](Compendium/Mechanics/CLI/spells/sunburst-xphb.md)

> [!embed-spell]- Swift Quiver
> ![Swift Quiver](Compendium/Mechanics/CLI/spells/swift-quiver-xphb.md)

> [!embed-spell]- Symbol
> ![Symbol](Compendium/Mechanics/CLI/spells/symbol-xphb.md)

> [!embed-spell]- Synaptic Static
> ![Synaptic Static](Compendium/Mechanics/CLI/spells/synaptic-static-xphb.md)

## T

> [!embed-spell]- Tasha's Bubbling Cauldron
> ![Tasha's Bubbling Cauldron](Compendium/Mechanics/CLI/spells/tashas-bubbling-cauldron-xphb.md)

> [!embed-spell]- Tasha's Hideous Laughter
> ![Tasha's Hideous Laughter](Compendium/Mechanics/CLI/spells/tashas-hideous-laughter-xphb.md)

> [!embed-spell]- Telekinesis
> ![Telekinesis](Compendium/Mechanics/CLI/spells/telekinesis-xphb.md)

> [!embed-spell]- Telepathy
> ![Telepathy](Compendium/Mechanics/CLI/spells/telepathy-xphb.md)

> [!embed-spell]- Teleport
> ![Teleport](Compendium/Mechanics/CLI/spells/teleport-xphb.md)

> [!embed-spell]- Teleportation Circle
> ![Teleportation Circle](Compendium/Mechanics/CLI/spells/teleportation-circle-xphb.md)

> [!embed-spell]- Tenser's Floating Disk
> ![Tenser's Floating Disk](Compendium/Mechanics/CLI/spells/tensers-floating-disk-xphb.md)

> [!embed-spell]- Thaumaturgy
> ![Thaumaturgy](Compendium/Mechanics/CLI/spells/thaumaturgy-xphb.md)

> [!embed-spell]- Thorn Whip
> ![Thorn Whip](Compendium/Mechanics/CLI/spells/thorn-whip-xphb.md)

> [!embed-spell]- Thunderclap
> ![Thunderclap](Compendium/Mechanics/CLI/spells/thunderclap-xphb.md)

> [!embed-spell]- Thunderous Smite
> ![Thunderous Smite](Compendium/Mechanics/CLI/spells/thunderous-smite-xphb.md)

> [!embed-spell]- Thunderwave
> ![Thunderwave](Compendium/Mechanics/CLI/spells/thunderwave-xphb.md)

> [!embed-spell]- Time Stop
> ![Time Stop](Compendium/Mechanics/CLI/spells/time-stop-xphb.md)

> [!embed-spell]- Toll the Dead
> ![Toll the Dead](Compendium/Mechanics/CLI/spells/toll-the-dead-xphb.md)

> [!embed-spell]- Tongues
> ![Tongues](Compendium/Mechanics/CLI/spells/tongues-xphb.md)

> [!embed-spell]- Transport via Plants
> ![Transport via Plants](Compendium/Mechanics/CLI/spells/transport-via-plants-xphb.md)

> [!embed-spell]- Tree Stride
> ![Tree Stride](Compendium/Mechanics/CLI/spells/tree-stride-xphb.md)

> [!embed-spell]- True Polymorph
> ![True Polymorph](Compendium/Mechanics/CLI/spells/true-polymorph-xphb.md)

> [!embed-spell]- True Resurrection
> ![True Resurrection](Compendium/Mechanics/CLI/spells/true-resurrection-xphb.md)

> [!embed-spell]- True Seeing
> ![True Seeing](Compendium/Mechanics/CLI/spells/true-seeing-xphb.md)

> [!embed-spell]- True Strike
> ![True Strike](Compendium/Mechanics/CLI/spells/true-strike-xphb.md)

> [!embed-spell]- Tsunami
> ![Tsunami](Compendium/Mechanics/CLI/spells/tsunami-xphb.md)

## U

> [!embed-spell]- Unseen Servant
> ![Unseen Servant](Compendium/Mechanics/CLI/spells/unseen-servant-xphb.md)

## V

> [!embed-spell]- Vampiric Touch
> ![Vampiric Touch](Compendium/Mechanics/CLI/spells/vampiric-touch-xphb.md)

> [!embed-spell]- Vicious Mockery
> ![Vicious Mockery](Compendium/Mechanics/CLI/spells/vicious-mockery-xphb.md)

> [!embed-spell]- Vitriolic Sphere
> ![Vitriolic Sphere](Compendium/Mechanics/CLI/spells/vitriolic-sphere-xphb.md)

## W

> [!embed-spell]- Wall of Fire
> ![Wall of Fire](Compendium/Mechanics/CLI/spells/wall-of-fire-xphb.md)

> [!embed-spell]- Wall of Force
> ![Wall of Force](Compendium/Mechanics/CLI/spells/wall-of-force-xphb.md)

> [!embed-spell]- Wall of Ice
> ![Wall of Ice](Compendium/Mechanics/CLI/spells/wall-of-ice-xphb.md)

> [!embed-spell]- Wall of Stone
> ![Wall of Stone](Compendium/Mechanics/CLI/spells/wall-of-stone-xphb.md)

> [!embed-spell]- Wall of Thorns
> ![Wall of Thorns](Compendium/Mechanics/CLI/spells/wall-of-thorns-xphb.md)

> [!embed-spell]- Warding Bond
> ![Warding Bond](Compendium/Mechanics/CLI/spells/warding-bond-xphb.md)

> [!embed-spell]- Water Breathing
> ![Water Breathing](Compendium/Mechanics/CLI/spells/water-breathing-xphb.md)

> [!embed-spell]- Water Walk
> ![Water Walk](Compendium/Mechanics/CLI/spells/water-walk-xphb.md)

> [!embed-spell]- Web
> ![Web](Compendium/Mechanics/CLI/spells/web-xphb.md)

> [!embed-spell]- Weird
> ![Weird](Compendium/Mechanics/CLI/spells/weird-xphb.md)

> [!embed-spell]- Wind Walk
> ![Wind Walk](Compendium/Mechanics/CLI/spells/wind-walk-xphb.md)

> [!embed-spell]- Wind Wall
> ![Wind Wall](Compendium/Mechanics/CLI/spells/wind-wall-xphb.md)

> [!embed-spell]- Wish
> ![Wish](Compendium/Mechanics/CLI/spells/wish-xphb.md)

> [!embed-spell]- Witch Bolt
> ![Witch Bolt](Compendium/Mechanics/CLI/spells/witch-bolt-xphb.md)

> [!embed-spell]- Word of Radiance
> ![Word of Radiance](Compendium/Mechanics/CLI/spells/word-of-radiance-xphb.md)

> [!embed-spell]- Word of Recall
> ![Word of Recall](Compendium/Mechanics/CLI/spells/word-of-recall-xphb.md)

> [!embed-spell]- Wrathful Smite
> ![Wrathful Smite](Compendium/Mechanics/CLI/spells/wrathful-smite-xphb.md)

## Y

> [!embed-spell]- Yolande's Regal Presence
> ![Yolande's Regal Presence](Compendium/Mechanics/CLI/spells/yolandes-regal-presence-xphb.md)

## Z

> [!embed-spell]- Zone of Truth
> ![Zone of Truth](Compendium/Mechanics/CLI/spells/zone-of-truth-xphb.md)
