```statblock
name: Pirate Captain
size: Medium
type: humanoid
subtype: any race ([[Pirate]])
alignment: any non-lawful alignment
ac: 16
hp: 112
hit_dice: 15d8+45
speed: 30 ft.
stats: [18, 14, 16, 14, 12, 16]
saves:
  - strength: 7
  - dexterity: 5
  - constitution: 6
skillsaves:
  - athletics: 7
  - deception: 6
  - intimidation: 6
  - perception: 4
senses: passive Perception 14
languages: any two languages
source: "Ghosts of Saltmarsh"
cr: 9
spells:
  - "The captain is a 6th-level spellcaster. Its spellcasting ability is Charisma (spell save DC 14, +6 to hit with spell attacks). It knows the following bard spells:"
  - "Cantrips (at will): friends, mage hand, vicious mockery"
  - "1st level (4 slots): charm person, disguise self, heroism, sleep"
  - "2nd level (3 slots): hold person, misty step, silence"
  - "3rd level (3 slots): hypnotic pattern, major image"
traits:
  - name: Legendary Resistance (3/Day)
    desc: "If the captain fails a saving throw, it can choose to succeed instead."
actions:
  - name: Multiattack
    desc: "The captain makes three attacks: two with its cutlass and one with its dagger."
  - name: Cutlass
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d8 + 4) slashing damage."
  - name: Dagger
    desc: "Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60 ft., one target. Hit: 6 (1d4 + 4) piercing damage."
legendary_actions:
  - name: Cutlass Attack
    desc: "The captain makes one cutlass attack."
  - name: Feint (Costs 2 Actions)
    desc: "The captain makes a deceptive gesture toward an enemy it can see within 30 feet. That enemy must succeed on a DC 14 Wisdom saving throw or become frightened until the end of its next turn."
  - name: Rally (Costs 3 Actions)
    desc: "The captain shouts a rallying cry. Each ally within 30 feet that can hear the captain gains 7 (2d6) temporary hit points."
```
