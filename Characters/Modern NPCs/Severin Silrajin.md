---
tags:
  - "#HotDQ"
aliases:
  - Severin
---

```statblock
columns: 1
forceColumns: true
layout: Basic 5e Layout
name: Severin
source: HotDQ
size: Medium
type: humanoid
subtype: human
alignment: neutral evil
ac: 16
hp: 150
hit_dice: 20d8 + 60
speed: 30 ft.
stats:
  - 10
  - 13
  - 16
  - 17
  - 12
  - 20
saves:
  - Dexterity: 5
  - Wisdom: 5
skillsaves:
  - Arcana: 7
  - Religion: 7
damage_vulnerabilities: ""
damage_resistances: acid, cold, lighting poison; bludgeoning, piercing, and slashing damage from nonmagical weapons
damage_immunities: fire
condition_immunities: charmed, frightened, poisoned
senses: dark vision 60ft., passive Perception 11
languages: Common, Draconic, Infernal
cr: "11"
traits:
  - name: Special Equipment
    desc: [[Severin]] has the [[Tarcian Headpiece]]
    attack_bonus: 0
  - name: Draconic Majesty
    desc: [[Severin]] adds his Charisma bonus to his AC (included)
    attack_bonus: 0
  - name: Ignite Enemy
    desc: If [[Severin]] deals fire damage to a creature while wearing the [[Tarcian Headpiece]], the target catches fire. At the start of each of its turns the burning target takes 5 (1d10) fire damage. A creature writhing reach of the fire can use an action to extinguish it.
    attack_bonus: 0
  - name: Legendary Resistance (5/Day)
    desc: While wearing the [[Tarcian Headpiece]], if Severin fails a saving throw, he can choose to succeed instead.
actions:
  - name: Burning Touch
    desc: "Melee Spell Attack: +5 to hit, reach 5 ft., one target. Hit: 18 (4d8) fire damage."
    attack_bonus: 5
    damage_dice: 4d8
    damage_bonus: 0
```

  - name: Flaming Orb
    desc: “Ranged Spell Attack:”
Ranged Spell Attack: +5 to hit, range 90 ft., one target. Hit: 40 (9d8) fire damage.    
    attack_bonus: 5
    damage_dice: 9d8
    damage_bonus: 0
  - name: Scorching Burst
    desc: “Severin chooses a point he can see within 60 feet of him. Each creature within 5 feet of that point must make a DC 17 Dexterity saving throw, taking 18 (4d8) fire damage on a failed save, or half as much on a successful one.”
    attack_bonus: 0
    damage_dice: 4d8
    damage_bonus: 0
legendary_actions:
“If Severin is wearing the [[Tarcian Headpiece]], he can take 3 legendary actions, choosing from the options below. Only one legendary astion option can be used at a time and only at the end of another creature’s turn. Severin regains spent legendary actions at the start of his turn.”
  - name: Attack
    desc: Severin makes one attack.
    attack_bonus: 0
  - name: Fiery Teleport (Costs 2 Actions)
    desc: ”Severin, along with any objects he is wearing or carrying, teleports up to 60 feet to an unoccupied space he can see. Each creature within 5 feet of Severin before he teleports takes 5 (1d10) fire damage.”
    attack_bonus: 0
  - name: Hellish Chains (Costs 3 Actions)
    desc: “Severin targets one creature haan see within 30 feet of him. The target is wrapped in magical chains of fire and retrained. The restrained target takes 21 (6d6) fire damage at the start of each of its turns. At the end of the its turns, the target can make a DC 17 Strength saving throw, ending the effect on itself on a success.”