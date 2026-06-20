```statblock
name: Drowned Assassin
size: Medium
type: undead
subtype: [[Drowned]]
alignment: chaotic evil
ac: 14
hp: 65
hit_dice: 10d8+20
speed: 30 ft., swim 30 ft.
stats: [11, 18, 15, 10, 10, 5]
skillsaves:
  - perception: 2
  - stealth: 8
damage_immunities: poison
condition_immunities: exhaustion, poisoned
senses: darkvision 60 ft., passive Perception 12
languages: understands the languages it knew in life but can't speak
source: "Ghosts of Saltmarsh"
cr: 4
traits:
  - name: Assassinate
    desc: "During its first turn, the assassin has advantage on attack rolls against any creature that hasn't taken a turn. Any hit the assassin scores against a surprised creature is a critical hit."
  - name: Undead Fortitude
    desc: "If damage reduces the assassin to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the assassin drops to 1 hit point instead."
actions:
  - name: Multiattack
    desc: "The assassin makes two dagger attacks."
  - name: Dagger
    desc: "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60 ft., one target. Hit: 6 (1d4 + 4) piercing damage, and the target must succeed on a DC 12 Constitution saving throw or take 10 (3d6) poison damage."
```
