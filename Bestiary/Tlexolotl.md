# Tlexolotl

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Tlexolotl | Elemental | 10 | 104 (11d12 + 33) | 15 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 1d10 + 7 + 4d8 | - | - |
| Tail | 1d8 + 7 + 4d6 | 19 | - |
| Pyroclasm {@recharge 5} | 6d6 + 6d6 | 15 | - |


**Multiattack.** The tlexolotl makes one Bite attack and one Tail attack.

**Bite.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}12 ({@damage 1d10 + 7}) piercing damage plus 18 ({@damage 4d8}) fire damage.

**Tail.** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}11 ({@damage 1d8 + 7}) bludgeoning damage plus 14 ({@damage 4d6}) fire damage. If the target is a Large or smaller creature, it must succeed on a {@dc 19} Strength saving throw or be pushed up to 10 feet away from the tlexolotl and knocked {@condition prone}.

**Pyroclasm {@recharge 5}.** Gouts of molten lava erupt from the tlexolotl's body. Each creature in a 30-foot-radius sphere centered on the tlexolotl must make a {@dc 15} Dexterity saving throw. On a failed saving throw, a creature takes 21 ({@damage 6d6}) fire damage and 21 ({@damage 6d6}) bludgeoning damage. On a successful saving throw, a creature takes half as much damage.

^Tags: #monster #type_elemental