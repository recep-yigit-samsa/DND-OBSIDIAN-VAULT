# Maurezhi

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Maurezhi | Unknown | 7 | 88 (16d8 + 16) | 15 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 2d10 + 3 | - | - |
| Claws | 2d8 + 3 | 12 | - |
| Raise Ghoul {@recharge 5} | - | - | - |


**Multiattack.** The maurezhi makes two attacks: one with its bite and one with its claws.

**Bite.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}14 ({@damage 2d10 + 3}) piercing damage. If the target is a humanoid, its Charisma score is reduced by {@dice 1d4}. This reduction lasts until the target finishes a short or long rest. The target dies if this reduces its Charisma to 0. It rises 24 hours later as a ghoul, unless it has been revived or its corpse has been destroyed.

**Claws.** {@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d8 + 3}) slashing damage. If the target is a creature other than an undead, it must succeed on a {@dc 12} Constitution saving throw or be {@condition paralyzed} for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Raise Ghoul {@recharge 5}.** The maurezhi targets one dead ghoul or ghast it can see within 30 feet of it. The target is revived with all its hit points.

^Tags: #monster #type_unknown