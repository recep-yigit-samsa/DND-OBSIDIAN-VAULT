# Tusked Skyfish

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Tusked Skyfish | Aberration | 4 | 102 (12d10 + 36) | 14 | walk: 5 ft., fly: {'number': 20, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Gore | 2d8 + 4 | - | - |
| Electrified Tentacles | 3d6 + 4 + 4d6 | 13 | - |
| Stench Spray {@recharge 5} | 6d6 | 13 | - |


**Multiattack.** The tusked skyfish makes one Gore attack and one Electrified Tentacles attack.

**Gore.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d8 + 4}) piercing damage.

**Electrified Tentacles.** {@atk mw} {@hit 6} to hit, reach 10 ft., one creature. {@h}14 ({@damage 3d6 + 4}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 13}) if it is a Medium or smaller creature. Until this grapple ends, the target is {@condition restrained} and takes 14 ({@damage 4d6}) lightning damage at the start of each of its turns, and the skyfish can't use its Electrified Tentacles on another target.

**Stench Spray {@recharge 5}.** The tusked skyfish sprays foul‑smelling liquid in a 20-foot line that is 5 feet wide. Each creature in that line must make a {@dc 13} Constitution saving throw. On a failure, a creature takes 21 ({@damage 6d6}) poison damage and is {@condition poisoned} for 1 minute. On a success, a creature takes half the damage and isn't {@condition poisoned}. If the saving throw fails by 5 or more, the creature falls {@condition unconscious} while {@condition poisoned} in this way. The {@condition unconscious} creature wakes up if it takes damage or if another creature takes an action to shake it awake. A {@condition poisoned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^Tags: #monster #type_aberration