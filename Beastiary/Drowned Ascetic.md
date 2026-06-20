```statblock
name: Drowned Ascetic
size: Medium
type: undead
subtype: [[Drowned]]
alignment: chaotic evil
ac: 14
hp: 52
hit_dice: 8d8+16
speed: 30 ft., swim 30 ft.
stats: [17, 18, 14, 7, 10, 5]
skillsaves:
  - athletics: 5
  - perception: 2
damage_immunities: poison
condition_immunities: exhaustion, poisoned
senses: darkvision 60 ft., passive Perception 12
languages: understands the languages it knew in life but can't speak
source: "Ghosts of Saltmarsh"
cr: 4
traits:
  - name: Relentless (Recharges after a Short or Long Rest)
    desc: "If the ascetic takes 20 damage or less that would reduce it to 0 hit points, it is reduced to 1 hit point instead."
  - name: Undead Fortitude
    desc: "If damage reduces the ascetic to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the ascetic drops to 1 hit point instead."
actions:
  - name: Multiattack
    desc: "The ascetic makes three unarmed strikes."
  - name: Unarmed Strike
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6 + 3) bludgeoning damage."
  - name: Stunning Strike (Recharge 6)
    desc: "One creature within 5 feet of the ascetic must succeed on a DC 13 Constitution saving throw or be stunned until the end of the ascetic's next turn."
```
