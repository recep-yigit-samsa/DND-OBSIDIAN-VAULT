# Rubezahl Demon

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Rubezahl Demon | Unknown | 10 | 136 (21d8 + 42) | 15 | walk: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 3d6 + 5 + 2d6 | - | - |
| Gore | 3d8 + 5 | 16 | - |
| Thunderstrike {@recharge 5} | 8d8 | 16 | - |


**Multiattack.** The rubezahl makes one Gore attack and two Claw attacks.

**Claw.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}15 ({@damage 3d6 + 5}) slashing damage plus 7 ({@damage 2d6}) lightning damage.

**Gore.** {@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}18 ({@damage 3d8 + 5}) piercing damage, and the target creature must succeed on a {@dc 16} Strength saving throw or be knocked {@condition prone}.

**Thunderstrike {@recharge 5}.** The rubezahl calls a sizzling bolt of lightning out of the sky, or from the air if underground or indoors, to strike a point the rubezahl can see within 150 feet of it. Each creature within 20 feet of that point must make a {@dc 16} Dexterity saving throw. On a failure, the creature takes 36 ({@damage 8d8}) lightning damage and is {@condition stunned} until the end of its next turn. On a success, the creature takes half the damage and isn't {@condition stunned}.

^Tags: #monster #type_unknown