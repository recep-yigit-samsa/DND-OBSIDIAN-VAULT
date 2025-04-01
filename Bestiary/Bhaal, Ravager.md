# Bhaal, Ravager

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Bhaal, Ravager | Beast | 24 | 351 (26d12 + 182) | 20 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 3d8 + 9 + 2d6 | 21 | - |
| Bite | 3d10 + 9 + 2d6 | 21 | - |
| Spines | 3d6 + 7 | 19 | - |


**Multiattack.** The ravager makes one Bite attack and then either two Claw attacks or two Spines attacks.

**Claw.** {@atk mw} {@hit 16} to hit, reach 5 ft., one target. {@h}22 ({@damage 3d8 + 9}) slashing damage plus 7 ({@damage 2d6}) necrotic damage. If the target is a creature, it must succeed on a {@dc 21} Constitution saving throw or have its hit point maximum reduced by an amount equal to the damage taken. The target dies if this attack reduces its hit point maximum to 0. The reduction lasts until removed by the {@spell greater restoration} spell or other magic.

**Bite.** {@atk mw} {@hit 16} to hit, reach 5 ft., one target. {@h}25 ({@damage 3d10 + 9}) piercing damage plus 7 ({@damage 2d6}) necrotic damage. If the target is a creature, it must succeed on a {@dc 21} Constitution saving throw or have its hit point maximum reduced by an amount equal to the damage taken. The target dies if this attack reduces its hit point maximum to 0. The reduction lasts until removed by the {@spell greater restoration} spell or other magic. Large or smaller creatures damaged by this attack are {@condition grappled} (escape {@dc 20}) and the ravager can't make another Bite attack until this grapple ends.

**Spines.** {@atk rw} {@hit 14} to hit, range 60/120 ft., one target. {@h}17 ({@damage 3d6 + 7}) piercing damage. If the target fails a {@dc 19} Constitution saving throw, they are {@condition stunned} until the end of their next turn.

^Tags: #monster #type_beast