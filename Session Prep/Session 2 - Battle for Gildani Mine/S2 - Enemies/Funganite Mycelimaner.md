```statblock
layout: Basic 5e Layout
name: Funganite Mycelimancer
size: Medium
type: plant
alignment: neutral evil
ac: 13
hp: 22
hit_dice: 5d8
speed: 25 ft.
stats:
  - 12
  - 10
  - 12
  - 12
  - 14
  - 8
saves:
  - constitution: 3
  - wisdom: 4
skillsaves:
  - nature: 3
  - perception: 4
senses: darkvision 60 ft., tremorsense 10 ft., passive Perception 14
languages: Understands Common and Sylvan but speaks only telepathically in vague impressions
damage_vulnerabilities: fire
condition_immunities: charmed, frightened, poisoned
cr: 1
actions:
  - name: Spore Bolt
    desc: "Ranged Spell Attack: +4 to hit, range 60 ft., one creature. Hit: 5 (1d8 + 1) poison damage."
  - name: Vine Snare (Recharge 5–6)
    desc: The Mycelimancer causes vines to erupt in a 10-foot radius within 30 feet. Each creature in that area must succeed on a DC 12 Strength saving throw or become restrained until the end of its next turn.
  - name: Sleep Spores (1/Day)
    desc: The Mycelimancer releases soporific spores in a 15-foot cone. Each creature must succeed on a DC 12 Constitution saving throw or fall unconscious for 1 minute. A creature awakens if it takes damage or another creature uses an action to shake or slap it awake.
reactions:
  - name: Spore Shield
    desc: When the Mycelimancer would take fire damage, it can use its reaction to release dense spores, granting itself half cover until the start of its next turn.
```