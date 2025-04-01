# Elder Brain Dragon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Elder Brain Dragon | Aberration | 22 | 350 (20d20 + 140) | 17 | walk: 40 ft., fly: {'number': 80, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 8 + 2d10 | - | - |
| Claw | 1d6 + 8 | - | - |
| Tentacle | 1d8 + 8 | 18 | - |
| Tadpole Brine Breath {@recharge 5} | 10d10 + 3d10 | 22 | - |


**Multiattack.** The dragon makes one Bite attack, two Claw attacks, and one Tentacle attack.

**Bite.** {@atk mw} {@hit 15} to hit, reach 15 ft., one target. {@h}19 ({@damage 2d10 + 8}) piercing damage plus 11 ({@damage 2d10}) psychic damage.

**Claw.** {@atk mw} {@hit 15} to hit, reach 10 ft., one target. {@h}11 ({@damage 1d6 + 8}) slashing damage.

**Tentacle.** {@atk mw} {@hit 15} to hit, reach 15 ft., one creature. {@h}12 ({@damage 1d8 + 8}) psychic damage. If the target is Huge or smaller, it is {@condition grappled} (escape {@dc 18}). The dragon can have up to four targets {@condition grappled} at a time.

**Tadpole Brine Breath {@recharge 5}.** The dragon exhales brine in a 120-foot line that is 15 feet wide. Each creature in that area must make a {@dc 22} Constitution saving throw, taking 55 ({@damage 10d10}) psychic damage on a failed save, or half as much damage on a successful one. On a success or failure, if the creature isn't a Construct or an Undead, it becomes infested with illithid tadpoles. While infested, the creature takes 16 ({@damage 3d10}) psychic damage at the start of each of its turns. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself after it succeeds on three of these saves. If the creature is targeted by magic that ends a curse or restores 40 hit points or more, the tadpoles infesting the creature are killed instantly, ending the effect on the creature. If a Humanoid is reduced to 0 hit points while infested, the creature is stable but remains {@condition unconscious} for {@dice 6d12} hours. When the period of unconsciousness ends, the creature transforms into a {@creature mind flayer} (see the Monster Manual) with all its hit points. Casting a {@spell wish} spell on the {@condition unconscious} creature rids it of the infestation and prevents it from turning into a mind flayer.

^Tags: #monster #type_aberration