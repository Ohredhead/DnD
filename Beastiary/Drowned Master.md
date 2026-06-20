```statblock
name: Drowned Master
size: Medium
type: undead
subtype: [[Drowned]]
alignment: chaotic evil
ac: 13
hp: 97
hit_dice: 13d8+39
speed: 30 ft., swim 30 ft.
stats: [18, 16, 16, 11, 12, 5]
saves:
  - constitution: 5
  - wisdom: 3
skillsaves:
  - athletics: 6
  - perception: 3
damage_immunities: poison
condition_immunities: exhaustion, poisoned
senses: darkvision 60 ft., passive Perception 13
languages: understands the languages it knew in life but can't speak
source: "Ghosts of Saltmarsh"
cr: 5
traits:
  - name: Undead Fortitude
    desc: "If damage reduces the master to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the master drops to 1 hit point instead."
  - name: Drowned One's Rage (Recharge after a Short or Long Rest)
    desc: "As a bonus action, the master enters a rage that lasts for 1 minute. While raging, it gains a +2 bonus to melee damage rolls and has resistance to bludgeoning, piercing, and slashing damage."
actions:
  - name: Multiattack
    desc: "The master makes three melee attacks."
  - name: Greatclub
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8 + 4) bludgeoning damage."
  - name: Ensnaring Strike (Recharge 5-6)
    desc: "Each creature within 10 feet of the master must succeed on a DC 14 Strength saving throw or be restrained until the end of the master's next turn."
```
