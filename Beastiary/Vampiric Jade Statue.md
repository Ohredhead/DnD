```statblock
name: Vampiric Jade Statue
size: Small
type: construct
alignment: neutral evil
ac: 13
hp: 30
hit_dice: 7d6+7
speed: 25 ft.
stats: [12, 14, 12, 3, 10, 3]
damage_immunities: "poison, psychic"
condition_immunities: "blinded, charmed, deafened, exhaustion, frightened, paralyzed, petrified, poisoned"
senses: blindsight 60 ft., passive Perception 10
languages: "understands the languages of its creator but can't speak"
source: "Ghosts of Saltmarsh"
cr: 2
traits:
  - name: Antimagic Susceptibility
    desc: "The statue is incapacitated while in the area of an antimagic field. If targeted by dispel magic, the statue must succeed on a Constitution saving throw against the caster's spell save DC or fall unconscious for 1 minute."
  - name: False Appearance
    desc: "While the statue remains motionless, it is indistinguishable from an ordinary jade statuette."
actions:
  - name: Multiattack
    desc: "The statue makes two claw attacks."
  - name: Claw
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6 + 2) slashing damage plus 3 (1d6) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the statue regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0."
```
