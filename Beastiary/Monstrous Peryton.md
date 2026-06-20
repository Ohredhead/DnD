```statblock
name: Monstrous Peryton
size: Large
type: monstrosity
alignment: chaotic evil
ac: 14
hp: 153
hit_dice: 18d10+54
speed: 20 ft., fly 80 ft.
stats: [20, 18, 16, 7, 16, 10]
saves:
  - constitution: 6
  - wisdom: 6
skillsaves:
  - perception: 6
  - stealth: 7
senses: passive Perception 16
languages: understands Elvish and Common but can't speak
source: "Ghosts of Saltmarsh"
cr: 8
traits:
  - name: Dive Attack
    desc: "If the peryton is flying and dives at least 30 feet toward a target and then hits it with a melee attack, the attack deals an extra 9 (2d8) damage."
  - name: Flyby
    desc: "The peryton doesn't provoke an opportunity attack when it flies out of an enemy's reach."
actions:
  - name: Multiattack
    desc: "The peryton makes two attacks: one with its gore and one with its talons."
  - name: Gore
    desc: "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 16 (2d10 + 5) piercing damage."
  - name: Talons
    desc: "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 14 (2d8 + 5) slashing damage."
  - name: Shadow Breath (Recharge 5-6)
    desc: "The peryton exhales shadowy vapors in a 30-foot cone. Each creature in that area must succeed on a DC 14 Constitution saving throw or be blinded and have disadvantage on saving throws while blinded this way. The blinded condition lasts until the target is hit by sunlight or until the target succeeds on a DC 14 Constitution saving throw at the end of one of its turns."
```
